Website hosted with github pages that generates (not on the fly, it was pregenerated) game music using a LSTM neural network.

## Data
The data used was about 1 hour of midi files for classic video game music (think Final Fantasy 7 and F-Zero).

## Preprocessing
I used music21 in order to get data from the midi files and again to create midi files from the output.

## Training
The neural net was trained for about 8 hours (57/200 epochs wanted). I used a Intel i3-8100 @ 3.60GHz. I used Keras to build the model.

## Sources
* [model and preprocessing](https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5)
* [data](https://bitmidi.com/)

## MUSIC!
[music](song.mp3)
