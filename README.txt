Max MSP sound feature extractor README file

This feature extractor aims to give sound descriptions in real-time from steaming audio signal.
It uses the IRCAM descriptors library, available here: https://forum.ircam.fr/projects/detail/max-sound-box/

This extractor is preset in order to work with Wekinator.

In this extractor, there are ten different descriptors that cover a large span of sound characteristics:

- Loudness
- Noisiness
- PerceptualOddToEvenRatio
- Sharpness
- Inharmonicity
- HarmonicEnergy
- NoiseEnergy
- TotalEnergy
- PerceptualSpectralCentroid
- HarmonicTristimulus

How it works: 
- choose an input signal with the radiogroup object (mic, noise or sound file)
- activate the extraction by clicking on the toggle box above the ircamdescriptors~ object
- activate DSP by clicking at the bottom right button of the Max window

You can download the project at this address: https://github.com/nicolasbrochec/wek-feature-extractor/
