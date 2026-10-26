---
title: AddVideoFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah frame video baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 209
url: /id/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) method

Membuat sebuah frame video baru dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame video baru, dalam point. |
| y | **float** | Koordinat y dari frame video baru, dalam point. |
| width | **float** | Lebar dari frame video baru, dalam point. |
| height | **float** | Tinggi dari frame video baru, dalam point. |
| fname | [System::String](../../../system/string/) | Jalur atau nama file video yang akan disematkan. |

### Nilai Kembali

[IVideoFrame](../../ivideoframe/) yang baru dibuat.

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) method

Membuat sebuah frame video baru dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame video baru, dalam point. |
| y | **float** | Koordinat y dari frame video baru, dalam point. |
| width | **float** | Lebar dari frame video baru, dalam point. |
| height | **float** | Tinggi dari frame video baru, dalam point. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) yang akan disematkan dalam frame video. |

### Nilai Kembali

[IVideoFrame](../../ivideoframe/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IVideoFrame](../../ivideoframe/)
* Kelas [String](../../../system/string/)
* Kelas [ShapeCollection](../)
* Kelas [IVideo](../../ivideo/)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)