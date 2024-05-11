Application: Google Ad Classifier to classify web promotions as one of 5 ad classifications:
* Product Promotion
* Service Promotion
* Sales Promotion
* Lead Generation
* Brand Awareness

Final Deliverable hosted on HuggingFace: [Ad Promotion Classifier](https://huggingface.co/tejasc/AdTypeClassifier)

This served as a final group project, tasked with creating a classification expert used for business applications based on Daniel Ringel's SyntheticExpert: [Creating Synthetic Experts with Generative Artificial Intelligence](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4542949)


This classifier was built using 27,000 webscraped Google Ads by various companies using Gustavo Silva's [Google Ads Scraper](https://console.apify.com/actors/N8vqwV9wL9wpIsLDz/console) on Apify. The data was cleaned and preprocessed before being labeled using OpenAI's GPT4.


The classifier was then trained using RandomForest, Support Vector Machine, Naive Bayes, and BERT. The final classification was built using BERT, specifically 'bert base uncased', documented in this paper: [](https://arxiv.org/abs/1810.04805)
