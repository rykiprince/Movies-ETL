# Movies-ETL
## Overview
### Create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database. Then, create an automated pipeline that takes in new data, performs the appropriate transformations and loads the data into existing tables.

### Write an ETL Function to Read Three Data Files
- The `wiki_movies_df` DataFrame

![wiki_movies_df](https://user-images.githubusercontent.com/66225050/129489918-5ef16156-aada-4f49-a5b8-f201ad8b07fe.png)

- The `kaggle_metadata` DataFrame

![kaggle_metadata](https://user-images.githubusercontent.com/66225050/129489922-42e99f46-bf10-43ea-b3fc-31b177780045.png)

- The `ratings` DataFrame

![ratings](https://user-images.githubusercontent.com/66225050/129489925-9f44dac7-79c3-4578-81eb-433da12d22b7.png)

### Extract and Transform the Wikipedia Data
- Cleaned wikipedia movies data as a DataFrame

![cleaned_wiki_movies](https://user-images.githubusercontent.com/66225050/129507520-a0d0f17a-876a-4838-9424-d35a3b7d9914.png)

- Add the columns from `wiki_movies_df` DataFrame to a list.

![cleaned_wiki_movies_columns](https://user-images.githubusercontent.com/66225050/129507527-970704ab-53a3-45c7-9d1e-3dfaefc142dc.png)

### Extract and Transform the Kaggle Data
- The `movies_with_ratings_df` DataFrame

![movies_with_ratings_df](https://user-images.githubusercontent.com/66225050/129507881-a67cac51-5d2c-4e7e-874b-32922a0a504e.png)

- The `movies_df` DataFrame

![movies_df](https://user-images.githubusercontent.com/66225050/129507937-8d5d33f1-9714-4979-b907-945548d85952.png)

### Create the Movie Database
- The `movies_query` counted rows

![movies_query.png](Resources/movies_query.png)

- The `ratings_query` counted rows

![ratings_query](Resources/ratings_query.png)
