---
title: InsertSummaryZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.
type: docs
weight: 157
url: /id/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metode

Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bingkai Summary Zoom. |
| x | **float** | Koordinat x bingkai Summary Zoom baru, dalam poin. |
| y | **float** | Koordinat y bingkai Summary Zoom baru, dalam poin. |
| width | **float** | Lebar bingkai Summary Zoom baru, dalam poin. |
| height | **float** | Tinggi bingkai Summary Zoom baru, dalam poin. |

### Nilai Kembali

[ISummaryZoomFrame](../../isummaryzoomframe/) yang baru dibuat.

## Catatan

Metode ini membuat bingkai Summary Zoom yang mengumpulkan tautan rangkuman untuk semua bagian dalam presentasi. 

Contoh ini menunjukkan pembuatan dan penyisipan objek Summary Zoom pada indeks yang ditentukan dalam sebuah koleksi (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)