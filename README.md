# Speech Language Identification

The project is a part of my internship and the research project at the Defence Research and Development Organisation - Scientific Analysis Group where I have to classify the speech audio samples in various languages spoken in India. The project will involve various techniques involving certain techniques to analyse the waveform, reduce the noise and use Machine Learning techniques to classify the audio clip.

### What can we used to extract features from a audio source

The audio signal is a three-dimensional signal in which three axes represent time, amplitude and frequency. Extraction of features is a very important part in analyzing and finding relations between different things. The data provided of audio cannot be understood by the models directly to convert them into an understandable format feature extraction is used. 

<p align="center"><img src = "images/audio_signal.png"></p>

## Techniques used to analyse the model

### Convolutional Neural Network (CNN) - Classification based on spectrograms
The method involves using Spectogram to analyse the spacial temporal data of the sound sample with the help of Librosa to generate images of the Spectogram graph and saving them. CNNs were used after the graphs were generated in the form of the images to study the patterns to classify the languages in the following categories.
<ul>
<li> English
<li> German
<li> Spanish
</ul>

#### Spectrogram from the Speech
<p align="center"><img src = "images/spectrogram.png"></p>

#### Prediction from a sample audio clip
<p align="center"><img src = "images/cnn_prediction_output.png"></p>

### Long Short Term Memory (RNN) - Classification based on raw wave forms
Recurrent networks can be used to study the sequential data of the speech samples but better results were found when using CNN

### Frameworks
<ul>
<li> Pytorch
<li> Pytorchvision
<li> Tensorflow
<li> Librosa
<li> Numpy
<li> Pandas
</ul>

### Resources
<ul>
<li> <a href = "https://www.kaggle.com/toponowicz/spoken-language-identification/downloads/spoken-language-identification.zip/1"> Kaggle dataset for Spoken Language Identification</a>
<li> <a href = "https://librosa.github.io/librosa/generated/librosa.feature.melspectrogram.html">Generating Spectrogram using Librosa</a>
<li> <a href = "https://arxiv.org/pdf/1812.00149.pdf">Using CNNs for audio classification</a>
<li> <a href = "https://www.tensorflow.org/alpha/tutorials/load_data/images">Creating dataset in Tensorflow</a>
<li> <a href = "https://pythonprogramming.net/cnn-tensorflow-convolutional-nerual-network-machine-learning-tutorial/">Developing CNN network in Tensorflow</a>
  
  
</ul>


