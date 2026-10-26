---
title: InsertSectionZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah frame Section Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.
type: docs
weight: 144
url: /id/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method

Membuat sebuah [Section](../../section/) Zoom frame baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan [Section](../../section/) Zoom frame. |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame baru, dalam poin. |
| width | **float** | Lebar [Section](../../section/) Zoom frame baru, dalam poin. |
| height | **float** | Tinggi [Section](../../section/) Zoom frame baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang direferensikan oleh [Section](../../section/) Zoom frame; harus menjadi bagian dari presentasi ini dan berisi setidaknya satu slide. |

### Nilai Kembali

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan pembuatan dan penyisipan objek [Section](../../section/) Zoom pada indeks yang ditentukan dalam sebuah koleksi (asumsikan terdapat setidaknya dua bagian dalam presentasi "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

Membuat sebuah [Section](../../section/) Zoom frame baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan [Section](../../section/) Zoom frame. |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame baru, dalam poin. |
| width | **float** | Lebar [Section](../../section/) Zoom frame baru, dalam poin. |
| height | **float** | Tinggi [Section](../../section/) Zoom frame baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang direferensikan oleh [Section](../../section/) Zoom frame; harus menjadi bagian dari presentasi ini dan berisi setidaknya satu slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Gambar yang ditampilkan dalam [Section](../../section/) Zoom frame. |

### Nilai Kembali

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan pembuatan dan penyisipan objek [Section](../../section/) Zoom pada indeks yang ditentukan dalam sebuah koleksi (asumsikan terdapat setidaknya dua bagian dalam presentasi "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)