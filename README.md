# SDR_Stereo_WBFM_Transmitter
A Stereo WBFM transmitter based on GNU Radio for test propose .
# Warning:This project is intended for testing purposes only; I assume no responsibility for any unauthorized transmission.
1. works with USRP B210 and GNU Radio Version 3.10 .
2. The defult sample rate is 8M and the baseband bandwith is 300khz.
3. This program will extract the audio signal from a 48 kHz, 16-bit stereo WAV file.
4. The program not only transmit audio but also transmit RDS infomation , the defult text is "TX TEST".
![example](/01.png)
![flowchart](/02.svg)
