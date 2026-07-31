---
title: AddSectionZoomFrame()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat sebuah frame Section Zoom baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 118
url: /id/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method


Membuat sebuah [Section](../../section/) Zoom frame baru dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame baru, dalam poin. |
| width | **float** | Lebar [Section](../../section/) Zoom frame baru, dalam poin. |
| height | **float** | Tinggi [Section](../../section/) Zoom frame baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang dirujuk oleh [Section](../../section/) Zoom frame; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.
## Remarks


Contoh ini menunjukkan penambahan objek [Section](../../section/) Zoom ke akhir koleksi (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Membuat sebuah [Section](../../section/) Zoom frame dengan gambar bawaan dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat x dari [Section](../../section/) Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari [Section](../../section/) Zoom frame baru, dalam poin. |
| width | **float** | Lebar [Section](../../section/) Zoom frame baru, dalam poin. |
| height | **float** | Tinggi [Section](../../section/) Zoom frame baru, dalam poin. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) yang dirujuk oleh [Section](../../section/) Zoom frame; harus termasuk dalam presentasi ini dan berisi setidaknya satu slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) yang akan ditampilkan di dalam [Section](../../section/) Zoom frame. |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) yang baru dibuat.
## Remarks


Contoh ini menunjukkan penambahan objek [Section](../../section/) Zoom ke akhir koleksi (asumsikan ada setidaknya dua bagian dalam presentasi "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)