---
title: AddPictureFrame()
second_title: Referensi API Aspose.Slides for C++
description: Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 404
url: /id/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metode

Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Menentukan jenis bentuk yang terdapat dalam [ShapeType](../../shapetype/), kecuali semua jenis garis:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | Koordinat x dari bingkai gambar, dalam poin. |
| y | **float** | Koordinat y dari bingkai gambar, dalam poin. |
| width | **float** | Lebar bingkai gambar, dalam poin. |
| height | **float** | Tinggi bingkai gambar, dalam poin. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) yang akan ditampilkan di dalam bingkai gambar. |

### Nilai Kembali

[IPictureFrame](../../ipictureframe/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPictureFrame](../../ipictureframe/)
* Kelas [IPPImage](../../ippimage/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)