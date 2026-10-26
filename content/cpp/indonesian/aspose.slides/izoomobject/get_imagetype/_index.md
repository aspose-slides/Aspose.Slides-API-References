---
title: get_ImageType()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan tipe gambar dari objek zoom. Baca ZoomImageType. Nilai default: Preview"
type: docs
weight: 1
url: /id/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() metode

Mendapatkan tipe gambar dari objek Zoom. Baca [ZoomImageType](../../zoomimagetype/). Nilai default: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Catatan

Menentukan apakah objek Zoom menggunakan pratinjau slide atau gambar sampul.

Contoh ini menunjukkan perubahan Image Type menjadi nilai Preview. Dalam kasus ini gambar saat ini dari objek Zoom berubah menjadi gambar slide:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Lihat Juga

* Enum [ZoomImageType](../../zoomimagetype/)
* Kelas [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)