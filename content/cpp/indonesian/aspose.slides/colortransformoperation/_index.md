---
title: ColorTransformOperation
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan operasi transformasi warna.
type: docs
weight: 5747
url: /id/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Mendefinisikan operasi transformasi warna.

```cpp
enum class ColorTransformOperation
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Tint | 0 | Mewarnai warna. Parameter berada dalam rentang antara 0 (warna asli) dan 1 (putih). |
| Shade | 1 | Memberi efek shade pada warna. Parameter berada dalam rentang antara 0 (warna asli) dan 1 (hitam). |
| Complement | 2 | Mengubah warna menjadi warna komplementer RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Mengubah warna menjadi warna terbalik. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Mengubah warna menjadi abu-abu dengan kecerahan yang sama. Parameter diabaikan. |
| SetAlpha | 5 | Menetapkan komponen alfa warna. Parameter berada dalam rentang antara 0 (transparan) dan 1 (tidak tembus). |
| AddAlpha | 6 | Menambahkan nilai parameter ke komponen alfa warna. Parameter berada dalam rentang antara -1 dan 1. |
| MultiplyAlpha | 7 | Mengalikan komponen alfa dengan nilai parameter. |
| SetHue | 8 | Mengubah komponen hue warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 360. |
| AddHue | 9 | Menambahkan nilai parameter ke komponen hue warna. Parameter berada dalam rentang antara -360 dan 360. |
| MultiplyHue | 10 | Mengalikan komponen hue dengan nilai parameter. |
| SetSaturation | 11 | Mengubah komponen saturasi warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1. |
| AddSaturation | 12 | Menambahkan nilai parameter ke komponen saturasi warna. Parameter berada dalam rentang antara -1 dan 1. |
| MultiplySaturation | 13 | Mengalikan komponen saturasi dengan nilai parameter. |
| SetLuminance | 14 | Mengubah komponen luminansi warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1. |
| AddLuminance | 15 | Menambahkan nilai parameter ke komponen luminansi warna. Parameter berada dalam rentang antara -1 dan 1. |
| MultiplyLuminance | 16 | Mengalikan komponen luminansi dengan nilai parameter. |
| SetRed | 17 | Mengubah komponen merah warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1. |
| AddRed | 18 | Menambahkan nilai parameter ke komponen merah warna. Parameter berada dalam rentang antara -1 dan 1. |
| MultiplyRed | 19 | Mengalikan komponen merah dengan parameter. |
| SetGreen | 20 | Mengubah komponen hijau warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 1. |
| AddGreen | 21 | Menambahkan parameter ke komponen hijau warna. Parameter berada dalam rentang antara -1 dan 1. |
| MultiplyGreen | 22 | Mengalikan komponen hijau dengan nilai parameter. |
| SetBlue | 23 | Mengubah komponen biru warna menjadi nilai parameter. Parameter berada dalam rentang antara 0 dan 360. |
| AddBlue | 24 | Menambahkan nilai parameter ke komponen biru warna. Parameter berada dalam rentang antara -1 dan 1. |
| MultiplyBlue | 25 | Mengalikan komponen biru dengan nilai parameter. |
| Gamma | 26 | Koreksi gamma. Parameter diabaikan. |
| InverseGamma | 27 | Koreksi gamma terbalik. Parameter diabaikan. |

## Lihat Juga

* Namespace [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)