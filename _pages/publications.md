---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
**[1] A 0.82 μVrms ultralow 1/f noise bandgap reference for a MEMS gyroscope**

by **JunJun Zou**, Qi Wei, Chunge Ju, Hua Liao, Haoyu Gu, Bowen Xing, Bin Zhou, Rong Zhang

_Microsystems & Nanoengineering 9, 48 (2023)._ [https://www.nature.com/articles/s41378-023-00505-3](https://www.nature.com/articles/s41378-023-00505-3)

**Abstract:** High-precision microelectromechanical system (MEMS) gyroscopes are significant in many applications. Bias instability (BI) is an important parameter that indicates the performance of a MEMS gyroscope and is affected by the 1/f noise of the MEMS resonator and readout circuit. Since the bandgap reference (BGR) is an important block in the readout circuit, reducing its 1/f noise is key to improving a gyroscope’s BI. In a traditional BGR, the error amplifier is applied to provide a virtual short-circuit point, but it introduces the main low-frequency noise sources. This paper proposes an ultralow 1/f noise BGR by removing the error amplifier and applying an optimized circuit topology. In addition, a simplified but accurate noise model of the proposed BGR is obtained to optimize the BGR’s output noise performance. To verify this design, the proposed BGR has been implemented in a 180 nm CMOS process with a chip area of 545 × 423 μm. The experimental results show that the BGR’s output integrated noise from 0.1 to 10 Hz is 0.82 μV and the thermal noise is 35 nV/√Hz. Furthermore, bias stability tests of the MEMS gyroscope fabricated in our laboratory with the proposed BGR and some commercial BGRs are carried out. Statistical results show that reducing the BGR’s 1/f noise can nearly linearly improve the gyroscope’s BI.[(PDF)](http://academicpages.github.io/files/micro&nano.pdf)

**[2] A 442.1 nVpp, 13.07 ppm/°C Ultra-Low Noise Bandgap Reference Circuit in 180 nm BCD Process**

by **JunJun Zou**, Qi Wei, Bin Zhou, Xiang Li, Chunge Ju, Rong Zhang, Zhiyong Chen

_2021 IEEE International Symposium on Circuits and Systems (ISCAS), (2021)._ [https://ieeexplore.ieee.org/abstract/document/9401631](https://ieeexplore.ieee.org/abstract/document/9401631)

**Abstract:** This paper proposed an ultra-low noise bandgap reference (BGR), which could achieve a sub-microvolt level of peak-to peak output noise in the low frequency region and have good load capacity. The noise performance is improved by using a negative feedback loop rather than traditional operational amplifier, which eliminates the noise from operational amplifier. Additionally, detailed analysis of noise is used to optimize the noise performance of the BGR. The driving ability is improved by using current mirrors to avoid the effect of load current on the behavior of BGR. Simulation results show operating at a 5 V supply voltage, over the range from -40 °C to 125 °C, output voltage of the BGR is 1.3345 V of mean value and temperature coefficient is 13.07 ppm/°C. The peak-to-peak output noise of the BGR is 442.1 nV in the band of 0.1 Hz to 10 Hz. The maximum output load current is 444.6 mA. MonteCarlo simulation illustrates process-invariance of this design.[(PDF)](http://academicpages.github.io/files/iscas.pdf)


 **[3] An Auto-Tuning Continuous-Time Bandpass Sigma-Delta Modulator with Signal Observation for MEMS Gyroscope Readout Systems** 

by Chunge Ju, Xiang Li, **JunJun Zou**, Qi Wei, Bin Zhou and Rong Zhang 

_Sensors 2020, 20(7)._ [https://www.mdpi.com/1424-8220/20/7/1973]( https://www.mdpi.com/1424-8220/20/7/1973)

**Abstract:** This paper presents the design and implementation of an auto-tuning continuous-time bandpass sigma-delta (ΣΔ) modulator for micro-electromechchanical systems (MEMS) gyroscope readout systems. Its notch frequency can well match the input signal frequency by adding a signal observation to the traditional ΣΔ modulator. The filter of the observation adopts the same architecture as that of the traditional ΣΔ modulator, allowing the two filters to have the same response to input signal change, which is converted into a control voltage on metal-oxide semiconductor (MOS) resistance in the filters. The automatic tuning not only works to solve the mismatch problem caused by process error and temperature variation, but can also be applied to the interface circuit of gyroscopes with different resonant frequencies. The circuit is implemented in a 0.18-μm complementary metal-oxide semiconductor (CMOS) process with a core area of 2.4 mm2. The improved modulator achieves a dynamic range of 106 dB, a noise floor below 120 dB and a maximum signal-to-noise and distortion ratio (SNDR) of 86.4 dB. The tuning capability of the chip is relatively stable under input signals from 6 to 15 kHz at temperatures ranging from −45 to 60 °C.[(PDF)](http://academicpages.github.io/files/sensors.pdf)
