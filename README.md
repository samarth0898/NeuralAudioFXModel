# Wavenet based guitar FX 
## Early Neural DSP Black-Box modeling using WaveNet 

Reference paper : Wright, A.; Damskägg, E.-P.; Juvela, L.; Välimäki, V. Real-Time Guitar Amplifier Emulation with Deep Learning. Appl. Sci. 2020, 10, 766. https://doi.org/10.3390/app10030766


## Black Box Modeling 
Black-box modelling is based on measuring the circuit’s response to some input signals, and creating a model which replicates the observed input-output mapping. Black-box models for VA modelling include block-oriented models, which are based on assumptions about the design of the modelled circuit [8–12]. model we proposed [23] for nonlinear cicuit black-box modelling, that was
based on the WaveNet convolutional neural network

Highlights about WaveNet

-  In order to deal with long-range temporal dependencies needed for raw audio generation, we develop new architectures based on dilated causal convolutions, which exhibit very large receptive fields.

- Deciding the receptive field using swept sine capture of the impulse response

Prominent hyperparameters 

- Channels used 
- Convolutional Layers 
- Dilation Patterns 


Gated Activation 


Divergence function 
- error to signal ratio (ESR)
