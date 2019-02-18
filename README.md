# Sebasi Open Corpus (Sebasi-OC)

The Sebasi Open Corpus is a Korean speech recognition (ASR) corpus generated from Sebasi talks. Sebasi is a Korean TV program with educational and inspirational video content. The generated corpus contains about 10 hours of speech audio-transcript pairs with 10 more hours to be uploaded in the future.

This corpus was generated using a corpus data ingestion and processing system called Pansori. Please refer to [this code repository](https://github.com/yc9701/pansori) and paper [1] for further information on the Pansori ASR corpus generation system.

The Pansori program utilized two techniques for improved alignment: forced alignment and silence detection. Forced alignment was performed with the [Montreal Forced Aligner](https://montreal-forced-aligner.readthedocs.io/en/latest/), a recently developed Kaldi-based forced aligner with multi-language support. To further improve alignment, silence detection from the [pydub](https://github.com/jiaaro/pydub) library for processing audio files was used.

The speech audio which will be included in the corpus are 16 bit FLAC files with sampling rate of 16 KHz. The actual audio files are currently undergoing final review, and the license is also being discussed with the original content holder. The final corpus will be uploaded once these steps are completed.

[1] Yoona Choi and Bowon Lee, "[Pansori: ASR Corpus Generation from Open Online Video Contents](https://arxiv.org/abs/1812.09798)," Proceedings of [IEEE Seoul Section Student Paper Contest 2018](http://sites.ieee.org/seoul/paper/), Hongik University, pp. 117--121, Nov. 2018.
