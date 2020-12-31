- Short time spectrum gives both source and system information. The envelope of the spectrum gives system information (i.e., resonances in terms of formant frequencies) and spectral ripples (fine variations) give source information (i.e., pitch harmonics). It is a real and even function of Ď.

- The linear prediction (LP) analysis models the vocal tract system. LP spectrum is observed to be an envelope of short time spectrum (smoothed version of short time spectrum) and the peaks in LP spectrum indicate the formant frequencies (resonances) of the vocal tract system. With observation it is evident that the LP spectrum is derived from an all-pole filter.

- The inverse spectrum is observed to be reciprocal of the LP spectrum. Therefore, we can observe the valleys corresponding to the peaks in LP spectrum. It is represented by an all-zero filter.

- For voiced speech segment its LP residual is observed to be periodic. In LP residual signal, peak amplitudes refers to closure of vocal folds (glottal closure), where the prediction is poor therefore its results as maximum error.


- The periodicity in LP residual also indicate the pitch information.

- LP residual is a result of passing the speech signal through inverse filter (i.e., removing the vocal tract information). This is also considered to be the excitation signal (source information).

- LP residual for unvoiced speech segment looks like random noise. This is because the unvoiced speech signal has no periodicity and looks like random noise (no relations among the samples).

- The basic property of the autocorrelation function (even symmetry) is evident in all (voiced/unvoiced speech and LP residual signals) the plots.


- The samples in a voiced speech segment are highly correlated, therefore we will observe the peaks other than center are also prominent. As voiced speech is periodic, it is inherited in its autocorrelation function also.


- In LP residual, the correlation among the samples is less, therefore its autocorrelation function contains the peaks at pitch rate. Hence autocorrelation function of a LP residual is useful for pitch computation.


The autocorrelation function of an unvoiced speech segment shows a major peak at the center and other peaks are not significant, since unvoiced speech signal appears like random signal.

The autocorrelation function for the LP residual of an unvoiced speech segment shows a dominant peak at the center and no other peaks in rest of the portion. This is because, unvoiced speech itself looks like random (no correlation among the samples) and its residual reflects still random.


Glottal pulse shape shows the change in volume of air. It is also referred to as glottal volume velocity.


From the glottal pulse waveform, it is observed that volume of air and its pressure will be maximum at the instant of closure. Following this is the opening of the vocal folds, as a result of which the air pressure decreases.

LP order determines to some extent the accuracy with which speech production mechanism is modeled.


LP analysis uses an all-pole model to characterize the vocal tract system by capturing the resonances with spectrum and source information with LP residual (inverse filter i.e., all-zero filter).


LP order determines the number of resonances that can be captured by the model. The maximum number of resonances captured by the model with LP order P is P/2.


The length of the vocal tract from glottis to lips is approximately 17 cm. This can generate four to five prominent resonances in 0-4 KHz range. These resonances can be captured with the LP model of order 10. We also should take care of radiation and windowing effects. Therefore with LP order 10-14 we can model the system by capturing required resonances. 

System with LP order more than 14 will introduce the spurious resonances, which leads improper representation of the vocal tract system.
