---
title: AddSummaryZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat frame Summary Zoom baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 157
url: /id/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) metode

Membuat sebuah frame Summary Zoom baru dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame Summary Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Summary Zoom baru, dalam poin. |
| width | **float** | Lebar dari frame Summary Zoom baru, dalam poin. |
| height | **float** | Tinggi dari frame Summary Zoom baru, dalam poin. |

### Nilai Kembalian

[ISummaryZoomFrame](../../isummaryzoomframe/) yang baru dibuat.

## Catatan

Metode ini membuat Summary Zoom baru dan menempatkan koleksi objek ke dalamnya untuk semua bagian dalam presentasi ini. 

Contoh ini menunjukkan cara menambahkan objek Summary Zoom ke akhir koleksi (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)