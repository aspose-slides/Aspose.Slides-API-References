---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ Referensi API
description: Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 443
url: /id/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metode

Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Menentukan jenis bentuk yang terkandung dalam [ShapeType](../../shapetype/), kecuali semua jenis garis:

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
| x | **float** | Koordinat x bingkai gambar, dalam poin. |
| y | **float** | Koordinat y bingkai gambar, dalam poin. |
| width | **float** | Lebar bingkai gambar, dalam poin. |
| height | **float** | Tinggi bingkai gambar, dalam poin. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) untuk ditampilkan dalam bingkai gambar. |

### Nilai Kembali

[IPictureFrame](../../ipictureframe/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)