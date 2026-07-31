---
title: PixelFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan format data warna sebuah piksel.
type: docs
weight: 326
url: /id/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Menentukan format data warna sebuah piksel.

```cpp
enum class PixelFormat
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Indexed | 65536 | Menentukan bahwa data piksel berisi nilai indeks warna yang berarti mereka adalah indeks ke warna dalam tabel warna sistem. |
| Gdi | 131072 | Menentukan bahwa data piksel berisi warna GDI. |
| Alpha | 262144 | Menentukan bahwa data piksel berisi nilai alpha yang tidak diprakalkulasi. |
| PAlpha | 524288 | Menentukan bahwa data piksel berisi nilai alpha yang diprakalkulasi. |
| Extended | 1048576 | Cadangan. |
| Canonical | 2097152 | Menentukan format piksel 32 bit per piksel dengan kedalaman warna 24-bit dan saluran alpha 8-bit. |
| Undefined | 0 | Menentukan bahwa format piksel tidak terdefinisi. |
| DontCare | 0 | Format piksel tidak ditentukan. |
| Format1bppIndexed | n/a | Menentukan bahwa format piksel adalah warna terindeks 1 bit per piksel. |
| Format4bppIndexed | n/a | Menentukan bahwa format piksel adalah warna terindeks 4 bit per piksel. |
| Format8bppIndexed | n/a | Menentukan bahwa format piksel adalah warna terindeks 8 bit per piksel. |
| Format16bppGrayScale | n/a | Menentukan bahwa format piksel adalah 16 bit per piksel. Informasi warna menentukan 65536 nuansa abu-abu. |
| Format16bppRgb555 | n/a | Menentukan bahwa format piksel adalah 16 bit per piksel dengan 5 bit untuk masing-masing komponen merah, hijau, dan biru serta bit yang tersisa tidak digunakan. |
| Format16bppRgb565 | n/a | Menentukan bahwa format piksel adalah 16 bit per piksel dengan 5 bit untuk merah, 6 bit untuk hijau, dan 5 bit untuk komponen biru. |
| Format16bppArgb1555 | n/a | Menentukan bahwa format piksel adalah 16 bit per piksel dengan 5 bit untuk masing-masing komponen merah, hijau, dan biru serta 1 bit untuk alpha. |
| Format24bppRgb | n/a | Menentukan bahwa format piksel adalah 24 bit per piksel dengan 8 bit untuk masing-masing komponen merah, hijau, dan biru. |
| Format32bppRgb | n/a | Menentukan bahwa format piksel adalah 32 bit per piksel dengan 8 bit untuk masing-masing komponen merah, hijau, dan biru serta 8 bit yang tersisa tidak digunakan. |
| Format32bppArgb | n/a | Menentukan bahwa format piksel adalah 32 bit per piksel dengan 8 bit untuk masing-masing komponen merah, hijau, dan biru serta 8 bit untuk alpha. |
| Format32bppPArgb | n/a | Menentukan bahwa format piksel adalah 32 bit per piksel dengan 8 bit untuk masing-masing komponen merah, hijau, dan biru serta 8 bit untuk alpha. Komponen merah, hijau, dan biru diprakalkulasi sesuai nilai komponen alpha. |
| Format48bppRgb | n/a | Menentukan bahwa format piksel adalah 48 bit per piksel dengan 16 bit untuk masing-masing komponen merah, hijau, dan biru. |
| Format64bppArgb | n/a | Menentukan bahwa format piksel adalah 64 bit per piksel dengan 16 bit untuk masing-masing komponen merah, hijau, dan biru serta 16 bit untuk alpha. |
| Format64bppPArgb | n/a | Menentukan bahwa format piksel adalah 64 bit per piksel dengan 16 bit untuk masing-masing komponen merah, hijau, dan biru serta 16 bit untuk alpha. Komponen merah, hijau, dan biru diprakalkulasi sesuai nilai komponen alpha. |
| Format32bppCMYK | n/a | Menentukan bahwa format piksel adalah 32 bit per piksel dengan 8 bit untuk masing-masing komponen cyan, magenta, kuning, dan key. |
| Max | 16 | Nilai maksimum enum ini. |

## Lihat Juga

* Ruang Nama [System::Drawing::Imaging](../)
* Perpustakaan [Aspose.Slides](../../)