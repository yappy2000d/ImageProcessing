<p align="right"><b><a href="README.md">[English]</a> / [中文]</b></p>

# Image Processing

[![C++11](https://img.shields.io/badge/C++-std11%20-blue.svg?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Docs](https://img.shields.io/badge/Docs-中文-blue.svg?style=flat-square)](https://yappy2000d.github.io/Image-Processing/)

這個庫是為影像處理實作課程而設計的，專注於簡化檔案讀寫與陣列操作，讓學生能夠專注於開發影像處理演算法，而無需處理複雜的影像格式。

## 為何不使用OpenCV？

OpenCV 是一個功能強大的影像處理庫，提供了許多現成的影像處理演算法。也因此課程作業往往會禁止使用 OpenCV，以確保學生能夠學習到影像處理的基本原理。

## Features

- **輕量**: 這個庫僅提供了最基本的功能，不包含任何複雜的演算法。
- **易於移植**: 這個庫僅使用標準庫，因此可以在任何支援C++11的編譯器上運行。

## 與Windows C++/CLI的比較

| 特性 | Windows C++/CLI | Image Processing |
| --- | --- | --- |
|  語言  | C++/CLI | 純C++11 |
|  GUI   | :white_check_mark: | :x: |
| 移植性 | :x: | :white_check_mark: |
|  開源  | :x: | :white_check_mark: |

為了維持精簡，這個庫不提供GUI介面，只提供了檔案讀寫與陣列操作的功能。與其使用Windows C++/CLI讓C++能夠調用.NET Framework，不如直接去使用C#。如果想製作一個GUI應用程式，那麼Qt或Tk會是移植性更好的選擇。
