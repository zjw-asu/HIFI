# HIFI
Here's the English translation:

---

This music player supports playback of 32-bit / 192 kHz audio tracks, drives high-impedance headphones, and delivers a high signal-to-noise ratio, high dynamic range, and high stereo separation.

The system is built around our own custom-designed ARM + CPLD playback motherboard, which supports the following formats:

- **WAV** — up to 192 kHz / 32-bit
- **FLAC** — up to 192 kHz / 24-bit
- **APE** — up to 96 kHz / 16-bit
- **MP3** and **DSF** — 44.1 kHz / 16-bit
- **DSD** — native hardware decoding

The DAC is the **AK4495**.

The firmware is adapted from the Alientek (正点原子) music-player reference example, with the following additions:

- Decoding support for the AK4495 DAC
- Native hardware DSD decoding
- Ported decoding algorithms for MP3, FLAC, and APE playback

---

			
	This music decoder supports 32bit/192K .wav,192K 24bit .FLAC ,96K 16bit .APE ,44.1K 16bit mp3, 2.4MHZ .DSF files.

	If you have any questions please email jiaweizuo@whu.edu.cn thanks.
					
