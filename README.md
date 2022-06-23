# Multi-dimensional Lyrical Analysis

This projects explores the lyrics of several rap and hip-hop songs across several years to try and understand:
- Lyrical similarity of prominent rap/hip-hop artists over the years, done using Cosine Similarity and Clustering 
- Musical influences of prominent rap/hip-hop artists over the years (i.e. if a given artist was inspired by another prior to his/her time based on lyrics), done using LDA and Jensen-Shannon distance.
- General themes for which song lyrics can be classified, used to identify the 'topics' or 'subjects' that any given rapper seems to veer toward and/or for songs from a given time period.  
- Change in music trends throughout the years in terms of the themes/topics rappers in general seem to discuss in their music.

## Dataset

The Spotify service was used for this project; several public playlists containing large volumes of hip-hop and rap music were curated and the [SpotiPy](https://spotipy.readthedocs.io/en/master/) Python API was used to retrieve track information. 

<br>

Code contained here is used within the course 'INSY 669 Text Analytics' of the MMA Program at McGill University.

This project was done in collaboration with [Carlos Fabbri](https://github.com/carlosfg97), [Matthieu J.](https://github.com/matthieujac), [Louis D'Hulst](https://github.com/louis-dhulst) and [Ananya Nair](https://github.com/nairaaa09)