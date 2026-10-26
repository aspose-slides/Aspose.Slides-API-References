---
title: AddZoomFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 92
url: /id/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) metode

Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Zoom baru, dalam poin. |
| width | **float** | Lebar frame Zoom baru, dalam poin. |
| height | **float** | Tinggi frame Zoom baru, dalam poin. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) yang direferensikan oleh frame Zoom; harus menjadi bagian dari presentasi ini. |

### Nilai Kembali

[IZoomFrame](../../izoomframe/) yang baru dibuat.

## Keterangan

Contoh ini menunjukkan penambahan objek Zoom ke akhir koleksi (asumsikan bahwa ada setidaknya dua slide dalam presentasi "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) metode

Membuat frame Zoom baru dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Zoom baru, dalam poin. |
| width | **float** | Lebar frame Zoom baru, dalam poin. |
| height | **float** | Tinggi frame Zoom baru, dalam poin. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) yang direferensikan oleh frame Zoom; harus menjadi bagian dari presentasi ini. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Gambar untuk slide yang direferensikan [IPPImage](../../ippimage/). |

### Nilai Kembali

[IZoomFrame](../../izoomframe/) yang baru dibuat.

## Keterangan

Contoh ini menunjukkan penambahan objek Zoom ke akhir koleksi (asumsikan bahwa ada setidaknya dua slide dalam presentasi "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IZoomFrame](../../izoomframe/)
* Kelas [ISlide](../../islide/)
* Kelas [IShapeCollection](../)
* Kelas [IPPImage](../../ippimage/)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)