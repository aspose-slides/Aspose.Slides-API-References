---
title: AddGroupShape()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi shape. Bingkai grup akan secara otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.
type: docs
weight: 391
url: /id/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() method


Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi shape. Bingkai grup akan secara otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Nilai Kembali

[IGroupShape](../../igroupshape/) yang baru dibuat.
## Catatan



Contoh berikut menunjukkan cara menambahkan grup shape ke slide PowerPoint [Presentation](../../presentation/). 
```cpp
// Membuat instance kelas Presentation
auto pres = System::MakeObject<Presentation>();

// Dapatkan slide pertama
auto slide = pres->get_Slides()->idx_get(0);
// Mengakses koleksi shape dari slide
auto slideShapes = slide->get_Shapes();
// Menambahkan grup shape ke slide
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Menambahkan shape di dalam grup shape yang ditambahkan
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Menambahkan bingkai grup shape
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Menulis file PPTX ke disk
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) method


Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individual, dan menambahkan grup hasil konversi ke akhir koleksi shape.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) yang berisi konten vektor untuk dikonversi menjadi shape. |
| x | **float** | Koordinat x dari bingkai grup, dalam poin. |
| y | **float** | Koordinat y dari bingkai grup, dalam poin. |
| width | **float** | Lebar bingkai grup, dalam poin. |
| height | **float** | Tinggi bingkai grup, dalam poin. |

### Nilai Kembali

[IGroupShape](../../igroupshape/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IGroupShape](../../igroupshape/)
* Kelas [ShapeCollection](../)
* Kelas [ISvgImage](../../isvgimage/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)