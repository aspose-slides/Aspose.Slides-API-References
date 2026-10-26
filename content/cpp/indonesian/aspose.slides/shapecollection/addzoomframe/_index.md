---
title: AddZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 105
url: /id/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method

Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | **float** | Lebar bingkai Zoom baru, dalam poin. |
| height | **float** | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The [ISlide](../../islide/) yang direferensikan oleh bingkai Zoom; harus termasuk dalam presentasi ini. |

### Nilai Kembalian

[IZoomFrame](../../izoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan penambahan objek Zoom ke akhir koleksi (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | **float** | Lebar bingkai Zoom baru, dalam poin. |
| height | **float** | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | The [ISlide](../../islide/) yang direferensikan oleh bingkai Zoom; harus termasuk dalam presentasi ini. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Gambar untuk slide [IPPImage](../../ippimage/) yang direferensikan. |

### Nilai Kembalian

[IZoomFrame](../../izoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan penambahan objek Zoom ke akhir koleksi (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)