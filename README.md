# LSTM_Musical_Generative_Model
CSE 190: Machine Learning for Music &amp; Audio

USAGE:  train.ipynb contains a Jupyter notebook to train the LSTM model 
        (train.py is the script equivalent, but remember to change memory_length)
        generate.ipynb contains a Jupyter notebook to generate midi files using trained model weights

The data directory contains the midi files used for training.

The output directory contains midi sequences formatted as 'output_<memory-length>_<total-epochs>_<index>'
  
Thhe weights directory contains snapshots of training weight .hd5f files with a short memory-length of 4, 
medium memory-length of 16, and a long memory-length of 32 (at 1, 50, 100 epochs). Where memory length 
corresponds to how far back the model is impacted by prior notes/chords appearing.
