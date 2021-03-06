# signal-recovery-noise
Implement RNN / LSTM on simulated wave data. This contains my part of a group project that worked with LIGO (Laser Inferometer Gravitational-Wave Observatory) data.

In this project, I artificially create a wave signal and add increasingly complex random noise to it to see which neural networks can extract the true signal the best. The methods are described in the "RNN-LSTM-with-keras" notebook. I was only responsible for the randomly created signals, but aided in data processing for the LIGO data. Those methods were applied by other members in this group project, outlined in the pdf of the final report produced (Using_Neural_Networks_to_Remove_60Hz_Noise_from_LIGO_Data.pdf). My findings are in the file: Noise-removal-and-signal-recovery-NN.pdf.

Credit to Rich Ormiston from LIGO for the basis of this project.

Methods: signal processing, recurrent neural network (RNN), long-short term memory (LSTM), power spectral density
