# video-search

- This project involves developing a video search system using AI techniques. It begins with creating a Python API for downloading YouTube videos and captions. 

- The core component is a video indexing pipeline that preprocesses videos, detects objects using pretrained models, and generates vector embeddings for detected objects using a convolutional autoencoder. These embeddings are then stored and indexed in a PostgreSQL database, set up using Docker. 

- The system aims to enable efficient searching of the video database using image queries, leveraging the vector embeddings to find similar images across the input videos. 

- An optional enhancement includes developing an improved method for segmenting videos into representative frames, potentially resulting in multiple embeddings per video for more precise searching.
