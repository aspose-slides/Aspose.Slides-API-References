---
title: AddGroupShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat shape grup kosong baru dan menambahkannya ke akhir koleksi shape. Frame grup akan secara otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.
type: docs
weight: 352
url: /id/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() metode

Membuat shape grup kosong baru dan menambahkannya ke akhir koleksi shape. Frame group\\u2019s akan secara otomatis menyesuaikan untuk menampung shape apa pun yang ditambahkan ke dalamnya.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### Nilai Kembali

[IGroupShape](../../igroupshape/) yang baru dibuat.

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metode

Membuat shape grup baru, mengonversi gambar SVG yang ditentukan menjadi shape individu, dan menambahkan grup yang dihasilkan ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) yang berisi konten vektor untuk dikonversi menjadi shape. |
| x | **float** | Koordinat x dari frame group\\u2019s, dalam poin. |
| y | **float** | Koordinat y dari frame group\\u2019s, dalam poin. |
| width | **float** | Lebar frame group\\u2019s, dalam poin. |
| height | **float** | Tinggi frame group\\u2019s, dalam poin. |

### Nilai Kembali

[IGroupShape](../../igroupshape/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [IShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)