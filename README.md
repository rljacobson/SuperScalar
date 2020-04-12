<p align="center">
<!--img src="src/icon/icon_main.png" height="150"-->

![src/icon/icon_main.png](src/icon/icon_main.png)
</p>

# SuperScaler 

<p align="center">
<img src="https://img.shields.io/badge/support-Windows-blue?logo=Windows">
<img src="https://img.shields.io/badge/support-macOS-blue?logo=Apple">
<img src="https://img.shields.io/badge/support-Linux-blue?logo=Linux">
<img src="https://img.shields.io/github/license/AaronFeng753/Waifu2x-Extension-GUI">
</p>

<p align="center">
<img src="https://img.shields.io/github/v/release/AaronFeng753/Waifu2x-Extension-GUI">
<img src="https://img.shields.io/github/commits-since/AaronFeng753/Waifu2x-Extension-GUI/latest">
<img src="https://img.shields.io/github/last-commit/AaronFeng753/Waifu2x-Extension-GUI">
</p>

This repo is a fork of 
[Waifu2x-Extension-GUI](https://github.com/AaronFeng753/Waifu2x-Extension-GUI). 
If you appreciate this software, consider giving a donation to Aaron Feng.


#### Differences from Waifu2x-Extension-GUI

* Changed the name to avoid confusion.
* Added ability to compile on macOS, Linux, and Windows.
* Added move-to-trash ability via [libtrashcan](https://github.com/robertguetzkow/libtrashcan).
* Removed branding & donation requests. (Visit 
[Waifu2x-Extension-GUI](https://github.com/AaronFeng753/Waifu2x-Extension-GUI) 
if you wish to donate.)


Original README from Waifu2x-Extension-GUI follows.
<hr>

<h4 align="center"> Supported Language: English, 简体中文, 日本語(機械翻訳) </h4>

<h4 align="center"> Supported graphics card brands: AMD, NVIDIA, Intel </h4>

### [中文版说明文档](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/README_CN.md#waifu2x-extension-gui)
### [Download](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/latest)---[Wiki](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/wiki)---[Change log](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/Change_log.md)---[Donate](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/Donate_page.md)

# What is Waifu2x-Extension-GUI?
`Image` & `GIF` & `Video` Super-Resolution using Deep Convolutional Neural Networks.

Based on `Waifu2x-ncnn-vulkan`,`SRMD-ncnn-Vulkan` and `Waifu2x-converter` . 

Thanks to waifu2x-ncnn-vulkan & SRMD-ncnn-Vulkan, Waifu2x-Extension-GUI could use any kind of gpu that support `Vulkan`, even Intel GPU. 

If your gpu doesn't support vulkan, you can use Waifu2x-converter, which is also intergrated into the Waifu2x-Extension-GUI.

![mainwindow](/Screenshot/mainwindow.jpg)

![processing](/Screenshot/processing.jpg)

![addsettings](/Screenshot/addsetiings.jpg)

#### Already been tested on `AMD` RX 550, `NVIDIA` GeForce GTX 1070 and `Intel` UHD 620.

# Features
- Easy to use graphical user interface
- Support batch processing of still pictures, gifs and videos
- Supports anime style and 3D realistic style images (that is, supports all image styles)
- Integrated multiple engines, strong hardware compatibility, support for computing with NVIDIA, Intel, AMD
- Unlimited scale ratio
- Custom output resolution (support pictures & GIF & video)
- Audio denoise.(for video)
- Flexible multi-thread management
- Processing video in segments, greatly reducing the hard disk space occupied when processing video.
- Support to save enlarged and noise-reduced pictures as .jpg and automatically perform lossless compression
- Automatically optimize the volume of the processed gif
- Compatibility test
- Multi-language (supports English, Simplified Chinese, Japanese)
- Support to store personalization settings and apply them automatically at startup
- Continually updated
- And more

# Samples

`All of these samples were processed using Waifu2x-ncnn-vulkan engine.`

### **`Image`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/image

### **`Video`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/video

### **`GIF`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/gif

#### Original 2D Anime Imgae 480x300 (.jpg 93.2 KB):
![Original Imgae](/Samples/image/Original_[480x300].jpg)

#### After 8x magnification, level 3 denoise and compress 3840x2400 (.jpg 525 KB):
![Scaled Imgae](/Samples/image/Waifu2x_8x_[3840x2400].jpg)

#### Comparison
![Comparison](/Samples/image/Comparison.png)

#### Original 3D Real-life Imgae 800x535 (.jpg 81.4 KB):
![Original Imgae](/Samples/image/deer.jpg)

#### After 4x magnification, level 2 denoise and compress 3200x2140 (.jpg 881 KB):
![Scaled Imgae](/Samples/image/deer_Waifu2x.jpg)

#### Original 3D Game Imgae 1200x630 (.jpg 168 KB):
![Original Imgae](/Samples/image/Cyberpunk-2077.jpg)

#### After 4x magnification, level 2 denoise 4800x2520 (.jpg 3.99 MB):
![Scaled Imgae](/Samples/image/Cyberpunk-2077_waifu2x_4x_2n_jpg.jpg)

#### Original GIF 500 x 372 (493 KB):
![Original GIF](/Samples/gif/2_original.gif)

#### After 2x magnification, level 2 denoise and gif optimize 1000 x 744 (3.77 MB):
![Original GIF](/Samples/gif/2_waifu2x_compressed.gif)

### `Github doesn't support play video online, pls check link below:`
### **`Video`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/video

# How to fix compatibility issue :
#### waifu2x-ncnn-vulkan: Re-install gpu driver or update it to the latest.
#### waifu2x-converter: Buy a new computer.
#### Anime4k: Install the latest JDK and JRE

# Integrated component(In releases):
- waifu2x-ncnn-vulkan version 20200224

- SRMD-ncnn-Vulkan version 20200224

- Anime4K Java v0.9 Beta

- ffmpeg version 4.2.2

- gifsicle version 1.92

- Waifu2x-converter version: v5.3.3

- ImageMagick 7.0.9-27-Q16-x64

- SoX 14.4.2-win32

# Credits:
- Donors: https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/Donate_list.md

- waifu2x-ncnn-vulkan: https://github.com/nihui/waifu2x-ncnn-vulkan

- SRMD-ncnn-Vulkan: https://github.com/nihui/srmd-ncnn-vulkan

- FFmpeg: https://ffmpeg.org/

- Gifsicle: https://www.lcdf.org/gifsicle/

- Anime4K: https://github.com/bloc97/Anime4K

- Waifu2x-converter: https://github.com/DeadSix27/waifu2x-converter-cpp

- ImageMagick: http://www.imagemagick.org/

- NSIS: https://nsis.sourceforge.io/

- Waifu2x-Extension: https://github.com/AaronFeng753/Waifu2x-Extension

- waifu2x: https://github.com/nagadomi/waifu2x

- SRMD: https://github.com/cszn/SRMD

- SoX: http://sox.sourceforge.net/

- Icons made by : Freepik (https://www.flaticon.com/authors/freepik) From Flaticon : https://www.flaticon.com/
