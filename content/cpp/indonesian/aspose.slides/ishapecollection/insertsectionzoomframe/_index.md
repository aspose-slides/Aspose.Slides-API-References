---
title: InsertSectionZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah frame Section Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.
type: docs
weight: 131
url: /id/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method

Membuat sebuah [Section](../../section/) Zoom frame baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol dimana [Section](../../section/) Zoom frame akan disisipkan. |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| width | **float** | Lebar dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| height | **float** | Tinggi dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang direferensikan oleh [Section](../../section/) Zoom frame; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |

### Nilai Kembalian

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.

## Keterangan

Contoh ini menunjukkan pembuatan dan penyisipan objek [Section](../../section/) Zoom pada indeks yang ditentukan dari sebuah koleksi (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

Membuat sebuah [Section](../../section/) Zoom frame baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol dimana [Section](../../section/) Zoom frame akan disisipkan. |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| width | **float** | Lebar dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| height | **float** | Tinggi dari [Section](../../section/) Zoom frame yang baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang direferensikan oleh [Section](../../section/) Zoom frame; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Gambar yang akan ditampilkan di dalam [Section](../../section/) Zoom frame. |

### Nilai Kembalian

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.

## Keterangan

Contoh ini menunjukkan pembuatan dan penyisipan objek [Section](../../section/) Zoom pada indeks yang ditentukan dari sebuah koleksi (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISectionZoomFrame](../../isectionzoomframe/)
* Kelas [ISection](../../isection/)
* Kelas [IShapeCollection](../)
* Kelas [IPPImage](../../ippimage/)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)