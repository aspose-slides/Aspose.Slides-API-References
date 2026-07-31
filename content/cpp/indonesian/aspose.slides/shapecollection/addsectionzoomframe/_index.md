---
title: AddSectionZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah Section Zoom frame baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 131
url: /id/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method

Membuat sebuah [Section](../../section/) Zoom frame baru dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame baru, dalam poin. |
| width | **float** | Lebar [Section](../../section/) Zoom frame baru, dalam poin. |
| height | **float** | Tinggi [Section](../../section/) Zoom frame baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang direferensikan oleh [Section](../../section/) Zoom frame; harus merupakan bagian dari presentasi ini dan berisi setidaknya satu slide. |

### Nilai Kembali

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan penambahan objek [Section](../../section/) Zoom ke akhir sebuah koleksi (asumsikan bahwa terdapat setidaknya dua bagian dalam presentasi "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

Membuat sebuah [Section](../../section/) Zoom frame baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame baru, dalam poin. |
| width | **float** | Lebar [Section](../../section/) Zoom frame baru, dalam poin. |
| height | **float** | Tinggi [Section](../../section/) Zoom frame baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang direferensikan oleh [Section](../../section/) Zoom frame; harus merupakan bagian dari presentasi ini dan berisi setidaknya satu slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) yang ditampilkan di dalam [Section](../../section/) Zoom frame. |

### Nilai Kembali

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan penambahan objek [Section](../../section/) Zoom ke akhir sebuah koleksi (asumsikan bahwa terdapat setidaknya dua bagian dalam presentasi "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISectionZoomFrame](../../isectionzoomframe/)
* Kelas [ISection](../../isection/)
* Kelas [ShapeCollection](../)
* Kelas [IPPImage](../../ippimage/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)