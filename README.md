# self-media-generation

## Dependencies
* python 3.8
* pytorch 2.01
* opencv-python 4.8.0.76
* spack 3.6.1

## Workflow 
![workflow2](https://github.com/tiuxuxsh76075/self-media-generation/assets/131826080/27f859a5-efba-4bcf-bc09-25cdc7571eaf)

**How to run:** 
1. Select 4 or 9 portrait photos you like.
2. Run the Main.py
3. You will get the processed photo like the third photo in the workflow and the vivid text with emoji😀.
4. Feel free to upload the content to Twitter or any social media platform.


**Training**

The new bert will be updating soon

**Attention**

We use a program I that designed(Accessing Mirror Sites with Crawlers) to enter a fake chatgpt to achive call LLM

**Validation**

In image caption, we use clip to compute a similarity between image and word to control the keyword generating.

## Examples in Twitter
![ex1](https://github.com/tiuxuxsh76075/self-media-generation/assets/131826080/9d242df2-8fd7-4757-a63c-0a92f2fccdd7)

## Sentiment Analysis and Topic Categorization
* Sentiment Analysis Net is on ./sentimentAnalysisNet, follow the instruction on the readme in the folder to train the net.
* Topic Categorization Net is on ./Bert_classification, follow the instruction on the readme in the folder to train the net.
