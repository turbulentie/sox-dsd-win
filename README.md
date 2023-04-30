```
  ████████          ██     ██       ███████    ████████ ███████  
 ██░░░░░░          ░░██   ██       ░██░░░░██  ██░░░░░░ ░██░░░░██ 
░██         ██████  ░░██ ██        ░██    ░██░██       ░██    ░██
░█████████ ██░░░░██  ░░███    █████░██    ░██░█████████░██    ░██
░░░░░░░░██░██   ░██   ██░██  ░░░░░ ░██    ░██░░░░░░░░██░██    ░██
       ░██░██   ░██  ██ ░░██       ░██    ██        ░██░██    ██ 
 ████████ ░░██████  ██   ░░██      ░███████   ████████ ░███████  
░░░░░░░░   ░░░░░░  ░░     ░░       ░░░░░░░   ░░░░░░░░  ░░░░░░░   
```

### SoX with DSD support for OS Windows.

## Table of Contents
 - [Introduction](#Introduction)
 - [Description](#Description)
 - [Prerequisites](#Prerequisites)
 - [Audio file formats](#Audio-file-formats)
 - [Audio effects and tools](#Audio-effects-and-tools)


# Introduction

SoX (Sound eXchange) is the Swiss Army knife of sound processing tools: it can convert sound files between many different file formats & audio devices, and can apply many sound effects & transformations, as well as doing basic analysis and providing input to more capable analysis and plotting tools.

# Description

Here located unofficial builds of the [SoX (Sound eXchange)](https://github.com/mansr/sox) audio tool with DSD support and other patches (including both DSF & DFF I/O and SDM sox "effect" to convert from PCM to DSD) for OS Windows only. Provided two Windows executable files for 32 & 64 bit systems. Binaries were cross-compiled on Linux using MinGW/gcc on fully static way.

- [x] DSF I/O
- [x] DFF I/O
- [x] SDM effect **to convert from PCM to DSD**

>_Note:_ `sox` is the best samplerate converter. IMHO.

# Prerequisites

SoX git sources located [here](https://github.com/mansr/sox).

The sox exectables included in this package makes use of the following projects:
- [PNG](http://www.libpng.org/pub/png)
- [Ogg Vorbis](http://www.vorbis.com)
- [FLAC](http://flac.sourceforge.net)
- [WavPack](http://www.wavpack.com)
- [libid3tag](http://www.underbit.com/products/mad)
- [libsndfile](http://www.mega-nerd.com/libsndfile)
- [Lame MP3 encoder](http://lame.sourceforge.net)
- [MAD MP3 decoder](http://www.underbit.com/products/mad)

# Audio file formats

The current release handles the following audio file formats:
* 8svx
* aif
* aifc
* aiff
* aiffc
* al
* amb
* au
* avr
* caf
* cdda
* cdr
* cvs
* cvsd
* cvu
* dat
* dff
* dsf
* dvms
* f32
* f4
* f64
* f8
* fap
* flac
* fssd
* gsm
* gsrt
* hcom
* htk
* ima
* ircam
* la
* lpc
* lpc10
* lu
* mat
* mat4
* mat5
* maud
* mp2
* mp3
* nist
* ogg
* paf
* prc
* pvf
* raw
* s1
* s16
* s2
* s24
* s3
* s32
* s4
* s8
* sb
* sd2
* sds
* sf
* sl
* sln
* smp
* snd
* sndfile
* sndr
* sndt
* sou
* sox
* sph
* sw
* txw
* u1
* u16
* u2
* u24
* u3
* u32
* u4
* u8
* ub
* ul
* uw
* vms
* voc
* vorbis
* vox
* w64
* wav
* wavpcm
* wsd
* wv
* wve
* xa
* xi

# Audio effects and tools

The audio effects/tools included in this release are as follows:
* allpass
* band
* bandpass
* bandreject
* bass
* bend
* biquad
* chorus
* channels
* compand
* contrast
* dcshift
* deemph
* delay
* dither
* divide+
* dop
* downsample
* earwax
* echo
* echos
* equalizer
* fade
* fir
* firfit+
* flanger
* gain
* highpass
* hilbert
* input#
* loudness
* lowpass
* mcompand
* noiseprof
* noisered
* norm
* oops
* output#
* overdrive
* pad
* phaser
* pitch
* rate
* remix
* repeat
* reverb
* reverse
* riaa
* sdm
* silence
* sinc
* spectrogram
* speed
* splice
* stat
* stats
* stretch
* swap
* synth
* tempo
* treble
* tremolo
* trim
* upsample
* vad
* vol
