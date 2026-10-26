---
title: AddVideoFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat frame video baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 170
url: /id/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) metode

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame video baru, dalam poin. |
| y | **float** | Koordinat y dari frame video baru, dalam poin. |
| width | **float** | Lebar dari frame video baru, dalam poin. |
| height | **float** | Tinggi dari frame video baru, dalam poin. |
| fname | [System::String](../../../system/string/) | Jalur atau nama file video yang akan disematkan. |

### Nilai Kembali

[IVideoFrame](../../ivideoframe/) yang baru dibuat.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metode

Membuat frame video baru dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame video baru, dalam poin. |
| y | **float** | Koordinat y dari frame video baru, dalam poin. |
| width | **float** | Lebar dari frame video baru, dalam poin. |
| height | **float** | Tinggi dari frame video baru, dalam poin. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) yang akan disematkan dalam frame video. |

### Nilai Kembali

[IVideoFrame](../../ivideoframe/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IVideoFrame](../../ivideoframe/)
* Kelas [String](../../../system/string/)
* Kelas [IShapeCollection](../)
* Kelas [IVideo](../../ivideo/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)