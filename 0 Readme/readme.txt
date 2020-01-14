################
# Introduction #
################

The material is bifurcated into 7 parts/folders:
0) Readme: Detailed instructions on how to run the code
1) Report: The final report which includes all details of the project
2) Code: The notebook file used to create the project
3) Generated songs: The final songs that were generated using the latest model
4) Input data: The collection of songs used to create the project
5) Models: Trained models saved as checkpoints
6) midi: The module required to parse the midi files
7) 7 Best generated songs (Meeting): set of songs that were selected for a demonstration to Mr. Avner Arad

####################
# Running the code #
####################

A) If you want to generate new songs from existing trained models

Steps to run the code:
1) Go to folder 4 Input data/Input songs here
2) Choose a song that you want to create variations for
3) Note the name of the song file
4) Go to folder '2 Code'
5) Create a copy of 'Triple stacked LSTM' using right mouse click and create a copy OR add this file to your drive and then create a copy OR open the file in google colab and select open in playground
6) Double click on the newly create file and from the top option 'Open with' choose 'Google Colaboratory'
7) In the top cell enter the song name as notes in Step 3
8) Run all cells and authenticate when prompted
9) Skip the 'Launch and run the session' and 'Save model' codes as we can directly load pre trained models
10) Load the model using the Load model cell and run the rest of the code
11) While generating, choose a bias of you own choice and use a random number as commented in the code
12) Download the song from the files section on the left hand side panel (click on '>' button)
13) Play the song in your local computer using VLC/Other media player

B) If you want to create a new model for a new song
Steps to run the code:
1) Go to folder 4 Input data/Input songs here
2) Upload your midi file to this folder
3) Note the name of the song file
4) Go to folder '2 Code'
5) Create a copy of 'Triple stacked LSTM' using right mouse click and create a copy OR add this file to your drive and then create a copy OR open the file in google colab and select open in playground
6) Double click on the newly create file and from the top option 'Open with' choose 'Google Colaboratory'
7) In the top cell enter the song name as notes in Step 3
8) Run all cells and authenticate when prompted
9) While generating, choose a bias of you own choice and use a random number as commented in the code
10) Download the song from the files section on the left hand side panel (click on '>' button)
11) Play the song in your local computer using VLC/Other media player