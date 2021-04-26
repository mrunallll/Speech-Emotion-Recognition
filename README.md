# Speech-Emotion-Recognition
*SER* - A combination of Signal Processing & Neural Networks

Speech Emotion Recognition (SER) is a way of comprehending human emotions from speech.

Speech, in the form of an audio signal, needs to be processed like any other type of data in order to infer emotions from it. 
Better Customer services, recommender systems, and many other applications are widening the scope of Speech Processing for Emotion Recognition.

In this project, RAVDESS dataset is used to train the model.
RAVDESS Data contains: 
2452 audio files, with 12 male speakers & 12 Female speakers, the lexical features (vocabulary) of the utterances are kept constant by speaking only 2 statements of equal lengths in 8 different emotions by all speakers.

The EMOTIONS are classified as:
* 0 = neutral
* 1 = calm
* 2 = happy
* 3 = sad
* 4 = angry
* 5= fearful
* 6 = disgust
* 7 = surprised

Important Terminology: 
1. _MFCC_ (Mel Frequency Cepstral Coefficients) - It represents hort-term power spectrum of a sound. This is taken on a Mel scale which is a scale that relates the perceived frequency of a tone to the actual measured frequency. It scales the frequency in order to match more closely to what the human ear can hear.
2. _Chroma_ - A Chroma vector is typically a 12-element feature vector indicating how much energy of each pitch class is present in the signal in a standard chromatic scale.
3. _Mel_ - Mel Spectrogram Frequency
