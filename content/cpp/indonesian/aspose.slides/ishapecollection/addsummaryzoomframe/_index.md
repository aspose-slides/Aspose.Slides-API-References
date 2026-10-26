---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat frame Summary Zoom baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 144
url: /id/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) metode


Membuat frame Summary Zoom baru dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | koordinat x dari frame Summary Zoom baru, dalam poin. |
| y | **float** | koordinat y dari frame Summary Zoom baru, dalam poin. |
| width | **float** | lebar frame Summary Zoom baru, dalam poin. |
| height | **float** | tinggi frame Summary Zoom baru, dalam poin. |

### Nilai Kembalian

[ISummaryZoomFrame](../../isummaryzoomframe/) yang baru dibuat.
## Catatan


Metode ini membuat frame Summary Zoom yang mengumpulkan tautan ringkasan untuk semua bagian dalam presentasi. 

Contoh ini menunjukkan cara menambahkan objek Summary Zoom ke akhir koleksi (asumsikan bahwa ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISummaryZoomFrame](../../isummaryzoomframe/)
* Kelas [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)