# kdrama-Recommendation-using-LLM

### Overview

This project develops a kdrama (Korean Drama) recommendation system using advanced natural language processing techniques. Utilizing sentence-transformers for generating embeddings and Faiss for efficient similarity searches, the system can recommend kdramas based on user input queries that describe their interests in genres, themes, or specific narratives.

### Features
Rich Contextual Understanding: Combines various metadata fields such as title, genre, cast, synopsis, and more to understand context deeply.
Efficient Searching: Implements Faiss, a library developed by Facebook AI Research, for fast and efficient similarity searches.
Scalability: Designed to easily scale with the addition of more kdrama entries or expanded metadata.
User-Friendly Interface: Simple function calls to get recommendations based on user preference.

### How It Works
The system uses the sentence-transformers library to convert textual descriptions of kdramas into dense vector embeddings. These embeddings capture the semantic meanings of the kdramas based on their descriptions. Faiss is then used to index these embeddings and perform fast similarity searches. When a user query is input, it is transformed into an embedding and compared against the indexed kdrama embeddings to find the most similar matches.
