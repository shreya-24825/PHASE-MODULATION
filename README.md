# PHASE-MODULATION-USING-SCILAB
## AIM

To write a program for Phase Modulation using SCILAB and to observe and verify its output waveform
## APPARATUS REQUIRED

Computer with i3 Processor or higher
SCILAB Software

## THEORY

Phase Modulation (PM) is a modulation technique in which the phase of the carrier signal is varied in accordance with the instantaneous amplitude of the modulating signal, while the amplitude of the carrier remains constant.

Phase Deviation (Δφ)

Phase deviation represents the maximum change in phase of the carrier signal.

Δφ = kp * Am

Where:

kp = Phase sensitivity (rad/volt)
Am = Amplitude of modulating signal
Modulation Index (mp)
mp = Δφ

For sinusoidal signals:

mp = kp * Am
PM Signal Equation
s(t) = Ac cos(2πfc t + kp m(t))

For sinusoidal modulating signal:

s(t) = Ac cos(2πfc t + mp sin(2πfm t))

Where:

Ac = Carrier amplitude
fc = Carrier frequency
fm = Modulating frequency
kp = Phase sensitivity
mp = Modulation index

## ALGORITHM

Define parameters:
Sampling frequency Fs
Time duration T
Carrier frequency fc
Modulating frequency fm
Phase sensitivity kp
Generate signals:
m(t) = sin(2πfm t)
c(t) = cos(2πfc t)
PM Modulation:
s(t) = cos(2πfc t + kp * m(t))

Plot all signals:
Modulating signal
Carrier signal
PM signal


## PROCEDURE

Refer to the algorithm and write the SCILAB code.
Open SCILAB software.
Create a new script file.
Enter the program and save it.
Execute the code.
Debug errors if any and re-run.
Observe the generated waveforms.

## OUTPUT
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-03 at 11 50 28 AM" src="https://github.com/user-attachments/assets/eec71ae7-084d-49e1-8a57-46a340b9a8b0" />




## RESULT
Thus code for phase modulation was executed in SCILAB and its output was verified.
