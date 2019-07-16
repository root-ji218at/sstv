SSTV Decoder
============

![](https://raw.githubusercontent.com/colaclanth/sstv/master/examples/m1.png)

A slow-scan television decoder that works on audio files rather than reading a soundcard (like most other decoders).
Currently supports the following modes:
* Martin 1, 2
* Scottie 1, 2, DX
* Robot 36, 72

Installation
------------

```
$ git clone https://github.com/colaclanth/sstv.git

$ python setup.py install
```

Usage
-----

```
$ sstv -d audio_file.wav -o result.png
```
