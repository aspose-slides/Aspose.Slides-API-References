---
title: set_ImageType()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menetapkan jenis gambar dari objek zoom. Tulis ZoomImageType. Nilai default: Preview"
type: docs
weight: 14
url: /id/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) metode

Menetapkan jenis gambar dari objek zoom. Tulis [ZoomImageType](../../zoomimagetype/). Nilai default: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Catatan

Menentukan apakah objek Zoom menggunakan pratinjau slide atau gambar sampul. 

Contoh ini menunjukkan mengubah Image Type ke nilai Preview. Dalam kasus ini gambar saat ini dari objek Zoom berubah menjadi gambar slide: 
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
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)