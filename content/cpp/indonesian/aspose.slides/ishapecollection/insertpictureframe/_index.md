---
title: InsertPictureFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat frame gambar baru yang berisi gambar yang ditentukan dan memasukkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 417
url: /id/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metode

Membuat frame gambar baru yang berisi gambar yang ditentukan dan memasukkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol di mana frame gambar akan disisipkan. |
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
| x | **float** | Koordinat x dari frame gambar, dalam poin. |
| y | **float** | Koordinat y dari frame gambar, dalam poin. |
| width | **float** | Lebar frame gambar, dalam poin. |
| height | **float** | Tinggi frame gambar, dalam poin. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) untuk ditampilkan dalam frame gambar. |

### Nilai Kembali

[IPictureFrame](../../ipictureframe/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPictureFrame](../../ipictureframe/)
* Kelas [IPPImage](../../ippimage/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)