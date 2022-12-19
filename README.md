# -GPT-2-fine-tuning-text-generation-with-Hugging-face.


https://colab.research.google.com/drive/1sk85pdrrrti2gLMZvd0e9zsmREfknxhq#scrollTo=-FQ1HItcT0rv 


# Objective:

The objective of this ICP is to GPT-2 fine tuning  text generation with Hugging face.

# Approaches

At first, necessary libraries are imported. Sample data (Amazon, Wikipedia) are extracted from Hugging face dataset and several transformer models are used  for Text generation.

# Datasets

For this ICP, datasets are extracted from Hugging Face website. datsets are Amazon and wikipedia.

# Results:

Results are generated with several libraries and accuracy is compared with training and validation sets. For the case of k = 50  and p = 0.5 gave the best result. And normal GPT2 performance is better than GPT2-squad-qg-hl.
![image](https://user-images.githubusercontent.com/70243598/206637833-4d1af5c6-6077-49ef-b7bf-14e9b37c40d5.png)
![image](https://user-images.githubusercontent.com/70243598/206638053-30a7ae4d-2543-424e-88f0-9eab897b3e11.png)

                                                  

# Challenges

For this icp, some models didn't work for the extracted dataset.

# Planned Work

At first, transformeris installed and implemented and GPT2 tokenizer is implemented and dataset is splitted. GPT2 accuracy is calculated for training and validation dataset 
and text is generated.
