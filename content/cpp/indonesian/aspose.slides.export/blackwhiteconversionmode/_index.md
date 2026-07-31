---
title: BlackWhiteConversionMode
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan opsi yang mengontrol bagaimana gambar slide akan dikonversi menjadi gambar bitonal.
type: docs
weight: 820
url: /id/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Menyediakan opsi yang mengontrol bagaimana gambar slide akan dikonversi menjadi gambar bitonal.

```cpp
enum class BlackWhiteConversionMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Default | 0 | Menentukan tidak ada algoritma konversi. Algoritma yang diimplementasikan dalam codec TIFF akan digunakan. (Default) |
| Dithering | 1 | Menentukan algoritma dithering (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Menentukan algoritma dithering Floyd-Steinberg. |
| Auto | 3 | Menentukan algoritma ambang otomatis yang dihitung (Otsu). |
| AutoOtsu | 4 | Menentukan algoritma ambang Otsu yang dihitung secara otomatis. |
| Threshold25 | 5 | Menentukan algoritma ambang statis (25%). |
| Threshold50 | 6 | Menentukan algoritma ambang statis (50%). |
| Threshold75 | 7 | Menentukan algoritma ambang statis (75%). |

## Lihat Juga

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)