# EvoDenoise: A Differential Evolution Approach for Denoising X Data 

> This gap underscores the novelty of adapting DE for domain-relevance-aware denoising in text, particularly health-related social media data, where noisy and informal language is prevalent.

## Fitness Function

> ![4](https://github.com/user-attachments/assets/d8f45665-bcd7-49f8-9cdf-53e7db17b4dc)


## Results: Validation

### Wordcloud 

>Looking at the word cloud visualization present in Figure 3, the word cloud effectively highlights the most frequently occurring terms in the denoised posts dataset. 
>The most prominent words include "cholera," "water," "hammanskraal," "outbreak," and "people," which appear in larger font sizes, indicating their higher frequency in the dataset. 
>These dominant terms clearly reflect the primary focus of the X conversations - a cholera outbreak that appears to be centred in Hammanskraal, South Africa.
>Geographic references are notably present, with "hammanskraal," "south," "tshwane," and potentially "city" appearing prominently, establishing the spatial context of the outbreak. 
>This suggests that the denoising algorithm has successfully preserved location-specific information that would be critical for spatial analysis of disease spread. 
>Health-related terminology is well-preserved in the denoised content, with words like "disease," "outbreak," "drinking," "clean," and "drink" featuring prominently. 
>This indicates that the EnhancedDifferentialEvolutionDenoiser has effectively maintained domain-relevant health terminology while removing noise.
>
![denoised_tweets_wordcloud](https://github.com/user-attachments/assets/c00f233a-0e6b-49f4-bb97-860dbb985d38)


### Original and denoised post lengths

>Illustrates the relationship between original and denoised post lengths, with the quantitative analysis revealing specific metrics about the transformation.
>The aver-age post length decreased from 25.63 words in the original posts to 16.94 words after denoising, representing a reduction of approximately 34%.
>This substantial decrease indicates effective noise removal. The median original post length (23.00 words) compared to the median denoised post length (16.00 words) shows a similar proportional reduction, confirming that the length reduction is consistent across the dataset rather than being skewed by outliers.
>Most posts are clustered in the lower left corner of the plot, indicating that the majority of posts are relatively short in both their original and denoised forms, which aligns with the calculated averages and medians.
>
![myplot](https://github.com/user-attachments/assets/75620b22-5456-427a-9824-d32c982d4fb0)
