# ANTiVax: A Groundbreaking Twitter Dataset for COVID-19 Vaccine Misinformation Detection

Introducing ANTiVax, a comprehensive dataset featuring over 15 million COVID-19 vaccine-related tweets and 15,000 meticulously labeled tweets aimed at detecting vaccine misinformation.

### What’s Inside:

- **VaccineTweets Folder**: Explore COVID-19 vaccine-related tweets collected weekly from November 2020 to July 2021.
  
- **Labeled Folder**: Dive into a treasure trove of over 15,000 tweets, each labeled for vaccine misinformation. The `is_misinfo` column clearly indicates whether a tweet is spreading misinformation.

![Framework](https://user-images.githubusercontent.com/47560178/127502306-4a9a0889-dc22-403e-957e-50f6a7978781.png)

### Explore the Full Study:
For a deep dive into the methodology and findings, check out our published paper: [Link to Paper](https://www.sciencedirect.com/science/article/pii/S0033350621004534)

## Citation:
Hayawi, Kadhim, Sakib Shahriar, Mohamed Adel Serhani, Ikbal Taleb, and Sujith Samuel Mathew. "ANTi-Vax: a novel Twitter dataset for COVID-19 vaccine misinformation detection." Public Health 203 (2022): 23-30.

---

### Abstract:

**Objective**:  
The COVID-19 pandemic has wreaked havoc globally, infecting millions and claiming lives. The advent of COVID-19 vaccines brought hope, but the spread of misinformation, especially on social media, has fueled vaccine hesitancy. This study introduces a pioneering machine learning framework for detecting COVID-19 vaccine misinformation on Twitter.

**Study Design**:  
We meticulously collected and annotated COVID-19 vaccine-related tweets and trained advanced machine learning algorithms to classify misinformation.

**Methods**:  
Leveraging a dataset of over 15,000 tweets, annotated and validated by medical experts, we tested various models, including XGBoost, LSTM, and the BERT transformer model.

**Results**:  
The BERT model outperformed others, achieving a remarkable F1-score of 0.98, with precision and recall scores of 0.97 and 0.98, respectively.
