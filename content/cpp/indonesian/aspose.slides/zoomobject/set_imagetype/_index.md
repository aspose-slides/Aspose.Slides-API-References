---
title: set_ImageType()
second_title: Aspose.Slides untuk Referensi API C++
description: "Mengatur jenis gambar dari objek zoom. Tulis ZoomImageType. Nilai default: Preview"
type: docs
weight: 14
url: /id/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) metode

Mengatur jenis gambar dari objek Zoom. Tulis [ZoomImageType](../../zoomimagetype/). Nilai default: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Catatan

Menentukan apakah objek Zoom menggunakan pratinjau slide atau gambar sampul.

Contoh berikut menunjukkan mengubah Image Type menjadi nilai Preview. Dalam hal ini gambar saat ini dari objek Zoom berubah menjadi gambar slide:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Lihat Juga

* Enum [ZoomImageType](../../zoomimagetype/)
* Kelas [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)