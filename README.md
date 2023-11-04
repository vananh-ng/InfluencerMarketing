# HWR
This is a student project with the MatchBrand company to implement NLP techniques to assist in the core business process (Influencer Marketing). This involves matching job openings to instagram influencers/content creators who will bring these jobs to their audience and help companies get new hires.

As a student team collaborating with MatchBrand, our primary goal is to optimize the job-matching process through automation. MatchBrand has presented three matching criteria to establish a matching score:

1. Matching social media profiles on jobs directly to apply.
2. Matching social media profiles with jobs that they could communicate about to their followers/network in a natural way.
3. Matching followers (e.g., comments) of social media profiles with jobs to apply.


**Motivation:**

In our collaboration with MatchBrand, our focus has been on the second criterion. We have utilized NLP techniques to develop a matching score that enables social media profiles to authentically communicate job offerings to their followers. This approach aims to create a more engaging and personalized talent acquisition experience for companies in need and job seekers, bridging the gap between the job market and the vast social media landscape. MatchBrand concentrates on working with microinfluencers (2k-10k followers), because of the higher average engagement rates including likes, comments, shares and saves of up to 10%.

**Main Question:**

The main question guiding our efforts was: How can we develop a robust matching process that generates a matching score for job offerings and Instagram profiles, resulting in three suitable Instagram profiles per job offering, along with a weight indicating which profile best aligns with the job offering?

**Contribution:**

Our collaborative efforts with MatchBrand aim to significantly improve talent acquisition by focusing on this specific matching criterion. By automating the process of identifying influencer profiles that align with a job offering and matching them accordingly, we can help to make the matching process, which has been conducted manually, more scalable. 

**Structure of our Repository**

Our repository is organized into four notebooks, each serving a specific purpose in the data preprocessing and topic modeling tasks and should be run in the following order:

**1. Jobs_preprocessing.ipynb**: This notebook contains the data preprocessing steps for the job dataset. It includes tasks like cleaning the data, handling missing values, remove stopwords, and translating the text to English for better matching with the Instagram dataset.

**2. Instagram_preprocessing.ipynb**: In this notebook, we perform the data preprocessing for the Instagram dataset. Similar to the Jobs_preprocessing notebook, we clean the data, handle any missing values, and ensure that the text is in a unified format for easy comparison with the job dataset.

**3. Kmeans_topicModeling.ipynb**: The Kmeans_topicModeling notebook focuses on the first approach we explored for topic modeling using k-means clustering. It includes explanations and demonstrations of how k-means clustering can be applied to discover topics or clusters in the job and Instagram datasets.

**4. LDA_topicModeling.ipynb**: This notebook presents the optimized approach we chose after trying out both k-means and Latent Dirichlet Allocation (LDA) for topic modeling. It explains our LDA approach and demonstrates how it outperforms k-means for the task of discovering meaningful topics in the job and Instagram datasets.

By organizing our repository with separate notebooks for data preprocessing and different topic modeling approaches, we maintain a clear and modular structure that allows us to easily understand and compare the results of each method. Additionally, this organization promotes reproducibility and allows others to comprehend our research and implementation processes effectively.
