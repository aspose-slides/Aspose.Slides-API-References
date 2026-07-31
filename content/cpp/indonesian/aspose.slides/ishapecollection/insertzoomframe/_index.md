---
title: InsertZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 105
url: /id/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) metode

Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bingkai Zoom. |
| x | **float** | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | **float** | Lebar bingkai Zoom baru, dalam poin. |
| height | **float** | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) yang direferensikan oleh bingkai Zoom. |

### Nilai Kembali

[IZoomFrame](../../izoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan pembuatan dan penyisipan objek Zoom pada indeks yang ditentukan dalam sebuah koleksi (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metode

Membuat bingkai Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bingkai Zoom. |
| x | **float** | Koordinat x dari bingkai Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai Zoom baru, dalam poin. |
| width | **float** | Lebar bingkai Zoom baru, dalam poin. |
| height | **float** | Tinggi bingkai Zoom baru, dalam poin. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) yang direferensikan oleh bingkai Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Gambar untuk slide [IPPImage](../../ippimage/) yang direferensikan. |

### Nilai Kembali

[IZoomFrame](../../izoomframe/) yang baru dibuat.

## Catatan

Contoh ini menunjukkan pembuatan dan penyisipan objek Zoom pada indeks yang ditentukan dalam sebuah koleksi (asumsikan ada setidaknya dua slide dalam presentasi "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)