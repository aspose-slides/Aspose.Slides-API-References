---
title: Zip64Mode
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan kapan harus menggunakan ekstensi format ZIP64 untuk file OpenXML.
type: docs
weight: 1119
url: /id/aspose.slides.export/zip64mode/
---
## Zip64Mode enum

Menentukan kapan harus menggunakan ekstensi format ZIP64 untuk file OpenXML.

```cpp
enum class Zip64Mode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Never | 0 | Jangan gunakan ekstensi format ZIP64. |
| IfNecessary | 1 | Gunakan ekstensi format ZIP64 jika diperlukan. |
| Always | 2 | Selalu gunakan ekstensi format ZIP64. |

## Catatan

File OpenXML adalah arsip ZIP yang memiliki batas 4 GB (2^32 byte) pada ukuran tidak terkompresi sebuah file, ukuran terkompresi sebuah file, dan total ukuran arsip, serta batas 65 535 (2^16-1) file dalam arsip. Ekstensi format ZIP64 meningkatkan batas tersebut menjadi 2^64. 

## Lihat Juga

* Namespace [Aspose::Slides::Export](../)
* Perpustakaan [Aspose.Slides](../../)