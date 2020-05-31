# Company_Project_Food_Safety
Business Motivation: 
Food Safety's mission is to protect Amazon customers from unsafe/low quality food products and contribute to build customer trust by ensuring safe, consistent, wholesome food and other consumables. One step towards accomplishing this mission at scale is early detection of unsafe/low quality food products from Amazon Customer Reviews. The Food Safety team, in partnership with the Heartbeat team,  work together to identify and human annotate customer reviews for potential issues. They are seeking a model to automate classification of Customer Reviews as Food Safety issues or not in the Grocery GL. The dataset available is a Food Safety gold standard dataset with Amazon ASIN data, review text and tagged as a Food Safety issue or not in the United States

A few notes:
    The dataset is relatively sparse and unbalanced
    
    Training Data Set: Gold Standard Dataset - 12 features (Product ASIN, Review star rating, Food Safety Issue, Review Text, Review Title, @nlp.sentenceCount, @product.brand, @product.countryOfOrigin, Product Width, Product Length, Product Height, Timestamp, Product Title (Analyzed).
    
