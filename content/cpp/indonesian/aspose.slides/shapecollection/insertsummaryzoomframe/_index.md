---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat frame Summary Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.
type: docs
weight: 170
url: /id/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method

Membuat frame Summary Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan frame Summary Zoom. |
| x | **float** | Koordinat x dari frame Summary Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Summary Zoom baru, dalam poin. |
| width | **float** | Lebar frame Summary Zoom baru, dalam poin. |
| height | **float** | Tinggi frame Summary Zoom baru, dalam poin. |

### Nilai Kembalian

[ISummaryZoomFrame](../../isummaryzoomframe/) yang baru dibuat.

## Keterangan

Metode ini membuat frame Summary Zoom yang mengumpulkan tautan ringkasan untuk semua bagian dalam presentasi. 

Contoh ini memperlihatkan cara membuat dan menyisipkan objek Summary Zoom pada indeks yang ditentukan dalam sebuah koleksi (asumsikan bahwa terdapat setidaknya dua bagian dalam presentasi "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)