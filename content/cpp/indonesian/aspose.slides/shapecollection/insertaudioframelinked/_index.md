---
title: InsertAudioFrameLinked()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 274
url: /id/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metode

Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bingkai audio. |
| x | **float** | Koordinat x dari bingkai audio baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai audio baru, dalam poin. |
| width | **float** | Lebar bingkai audio baru, dalam poin. |
| height | **float** | Tinggi bingkai audio baru, dalam poin. |
| fname | [System::String](../../../system/string/) | Jalur atau nama file audio eksternal yang akan dihubungkan. |

### Nilai Kembalian

[IAudioFrame](../../iaudioframe/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudioFrame](../../iaudioframe/)
* Kelas [String](../../../system/string/)
* Kelas [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)