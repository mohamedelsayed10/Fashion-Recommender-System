# Fashion Recommendation Systems

## Overview
Aims to develop three advanced recommendation systems for Twenty Too©, a company specializing in AI-as-a-service solutions for the fashion industry. The fashion industry is rapidly evolving with the integration of artificial intelligence (AI) technologies, enabling businesses to optimize operations, enhance customer experience, and drive sales growth. Offering AI-as-a-service solutions designed to address key challenges in the fashion sector, this project, commissioned by Twenty Too, involves the development of three distinct recommendation systems aimed at improving various aspects of the customer journey and business efficiency.
# dataset is confidential for  Twenty Too©

## Systems Developed
1. **Frequently Bought Together Recommender**: Uses the FP-Growth algorithm to suggest items that are often purchased together to complete the look. This model leverages historical purchase data to identify and suggest complementary products, designed to increase basket size and drive additional sales by presenting relevant product combinations.
   
2. **Similarity-Based Recommender**: Utilizes the CLIP and ALIGN models to recommend items based on similarity in appeal and look. This model focuses on product similarity, using advanced image and text analysis to recommend items that are visually and contextually similar, helping customers discover new products that align with their preferences, enhancing their shopping experience and increasing conversion rates.
   
3. **Personalization-Based Recommender**: Provides personalized recommendations using a two-tower model based on user demographics and history, as well as models that compute similarity based on user interactions and item embeddings from fashion CLIP. By understanding the unique preferences and behaviors of each customer, this model delivers highly relevant suggestions, fostering customer loyalty and satisfaction.

## Features
- **FP-Growth Algorithm**: Used for identifying items frequently bought together, enhancing cross-selling opportunities.
- **CLIP and ALIGN Models**: Employed to extract image and text embeddings, combined and stored in Pinecone vector database.
- **Two-Tower Model**: Enhances personalization by leveraging user demographics and history.
- **Similarity-Based on User Interactions**: Recommends products based on user behavior and preferences using collaborative filtering.
- **Similarity-Based on Item Embeddings**: Uses fashion CLIP embeddings to compute item similarity for recommendations.
- **Deployment**: All systems are deployed using Flask for the backend, and HTML/CSS for the frontend, ensuring a seamless user experience and reducing page load times by 30%.


