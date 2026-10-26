---
title: GetObjectStoringLocation()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan di mana objek harus disimpan. Metode ini dipanggil sekali untuk setiap id objek. Tidak dijamin tidak akan ada dua objek dengan data, semanticName, dan contentType yang sama tetapi dengan id yang berbeda.
type: docs
weight: 1
url: /id/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) metode

Menentukan di mana objek harus disimpan. Metode ini dipanggil sekali untuk setiap id objek. Tidak dijamin tidak akan ada dua objek dengan data, semanticName, dan contentType yang sama tetapi dengan id yang berbeda.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | **int32_t** | Id objek. Id ini unik untuk seluruh operasi penyimpanan. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data biner objek. Parameter ini dapat bernilai null, jika data biner objek belum dihasilkan. |
| semanticName | [System::String](../../../system/string/) | Beberapa teks singkat yang menjelaskan makna objek. Kontroler dapat menggunakan ini sebagai bagian dari nama objek eksternal, tetapi terserah dispatcher untuk memastikan nama tersebut unik dan hanya berisi karakter yang diizinkan. |
| contentType | [System::String](../../../system/string/) | tipe MIME objek. |
| recomendedExtension | [System::String](../../../system/string/) | Ekstensi nama file yang direkomendasikan untuk tipe MIME ini. |

### Nilai Kembali

Keputusan

## Lihat Juga

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [ILinkEmbedController](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)