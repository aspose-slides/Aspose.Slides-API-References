---
title: InsertAudioFrameLinked()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat frame audio baru yang ditautkan ke berkas audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 235
url: /id/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metode

Membuat frame audio baru yang ditautkan ke berkas audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan frame audio. |
| x | **float** | Koordinat x dari frame audio baru, dalam poin. |
| y | **float** | Koordinat y dari frame audio baru, dalam poin. |
| width | **float** | Lebar dari frame audio baru, dalam poin. |
| height | **float** | Tinggi dari frame audio baru, dalam poin. |
| fname | [System::String](../../../system/string/) | Jalur atau nama berkas audio eksternal yang akan ditautkan. |

### Nilai Kembali

[IAudioFrame](../../iaudioframe/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudioFrame](../../iaudioframe/)
* Kelas [String](../../../system/string/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)