---
title: CompressionLevel
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan tingkat kompresi ZIP untuk file OpenXML. Tingkat yang lebih tinggi memberikan kompresi yang lebih baik dengan biaya pemrosesan yang lebih lambat.
type: docs
weight: 846
url: /id/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

Menentukan tingkat kompresi ZIP untuk file OpenXML. Tingkat yang lebih tinggi memberikan kompresi yang lebih baik dengan biaya pemrosesan yang lebih lambat.

```cpp
enum class CompressionLevel
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Tidak ada kompresi yang diterapkan. File disimpan apa adanya. |
| Level1 | 1 | Kompresi tercepat dengan rasio kompresi terendah. |
| Level2 | 2 | Kompresi lebih cepat dengan rasio kompresi sedikit lebih baik daripada [CompressionLevel::Level1](./). |
| Level3 | 3 | Menyediakan kompresi yang lebih baik daripada [CompressionLevel::Level2](./) dengan dampak kinerja sedang. |
| Level4 | 4 | Menyediakan kompresi yang lebih baik daripada [CompressionLevel::Level3](./). |
| Level5 | 5 | Menyediakan kompresi yang ditingkatkan dibandingkan [CompressionLevel::Level4](./) dengan waktu pemrosesan tambahan. |
| Level6 | 6 | Kompresi standar, menawarkan keseimbangan yang baik antara kecepatan kompresi dan ukuran file. Tingkat kompresi default. |
| Level7 | 7 | Menyediakan kompresi yang lebih tinggi daripada [CompressionLevel::Level6](./) dengan pemrosesan yang lebih lambat. |
| Level8 | 8 | Menyediakan kompresi yang lebih tinggi daripada [CompressionLevel::Level7](./). |
| Level9 | 9 | Kompresi maksimum. Menghasilkan ukuran file terkecil dengan kecepatan pemrosesan paling lambat. |

## Lihat Juga

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)