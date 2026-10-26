---
title: Details_FileNotFoundException
second_title: Aspose.Slides untuk Referensi API C++
description: "Pengecualian yang dilempar ketika percobaan mengakses file yang tidak ada di disk gagal. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas FileNotFoundException sebagai gantinya. Jangan pernah membungkus instance kelas FileNotFoundException ke dalam System::SmartPtr."
type: docs
weight: 183
url: /id/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException kelas

Pengecualian yang dilempar ketika percobaan mengakses file yang tidak ada di disk gagal. Jangan pernah membuat instance kelas ini secara manual. Gunakan FileNotFoundException kelas sebagai gantinya. Jangan pernah membungkus instance FileNotFoundException kelas ke dalam [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Mengambil nama file yang menyebabkan pengecualian ini. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Lihat Juga

* Kelas [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Ruang nama [System::IO](../)
* Perpustakaan [Aspose.Slides](../../)