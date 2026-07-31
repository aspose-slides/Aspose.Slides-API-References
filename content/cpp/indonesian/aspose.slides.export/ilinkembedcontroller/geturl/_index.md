---
title: GetUrl()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan sebuah URL ke objek eksternal. Metode ini selalu dipanggil jika ILinkEmbedController::GetObjectStoringLocation mengembalikan LinkEmbedDecision::Link dan dapat dipanggil jika ILinkEmbedController::GetObjectStoringLocation mengembalikan LinkEmbedDecision::Embed tetapi penyematan tidak memungkinkan. Dapat dipanggil berkali-kali untuk id objek yang sama."
type: docs
weight: 14
url: /id/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) metode

Mengembalikan sebuah URL ke objek eksternal. Metode ini selalu dipanggil jika [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) mengembalikan [LinkEmbedDecision::Link](../../linkembeddecision/) dan dapat dipanggil jika [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) mengembalikan [LinkEmbedDecision::Embed](../../linkembeddecision/) tetapi penyematan tidak memungkinkan. Dapat dipanggil berkali-kali untuk id objek yang sama.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | **int32_t** | Id objek. Id ini bersifat unik untuk seluruh operasi. |
| referrer | **int32_t** | Id objek yang merujuk atau 0, jika objek dirujuk oleh dokumen akar. Dapat digunakan untuk menghasilkan tautan relatif. |

### Nilai Kembali

URL objek eksternal atau null jika objek ini harus diabaikan.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [ILinkEmbedController](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)