# Unsupervised_MachineLearning_for_SpotifyPlaylist


## Project Description --- Spotify Playlist Creation and Song Clustering

This project involves the analysis of a dataset of 5000 songs using machine learning techniques. The main objective is to cluster the songs based on their audio features and use this information to create a personalized Spotify playlist.
The project is divided into two main parts. The first part, implemented in Kmeans_5000songs.ipynb, uses the K-means algorithm to cluster the songs based on their audio features such as tempo, instrumentalness, acousticness, valence, and danceability. The second part, implemented in my_spotify_playlist.ipynb, uses the Spotipy library to interact with the Spotify API and create a personalized playlist.

## Technical Details

The project is implemented in Python and uses several libraries such as pandas for data manipulation, sklearn for machine learning, matplotlib for data visualization, and Spotipy for interacting with the Spotify API.
Here are the main steps followed in each part of the project:
		Kmeans_5000songs.ipynb:
	•	Import the CSV data containing song information
	•	Select relevant data columns for analysis
	•	Perform K-means clustering to group similar songs together
	•	Calculate and plot cluster centroids to understand the characteristics of each group
	•	Visualize clustering results with various plots
		my_spotify_playlist.ipynb:
	•	Install and setup Spotipy
	•	Authenticate with Spotify API
	•	Create a personalized playlist based on the clustering results

## Project Goals
The main goal of this project is to understand the patterns and characteristics of different songs by applying machine learning techniques. By clustering songs based on their audio features, we can discover groups of songs that have similar characteristics, which can be useful for music recommendation.
Another goal is to create a personalized Spotify playlist using the Spotipy library. By understanding the patterns in the data, we can recommend songs that the user might like and add them to a personalized playlist on Spotify.
