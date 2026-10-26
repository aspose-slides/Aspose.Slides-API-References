---
title: set_ZoomImage()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengatur gambar untuk objek zoom. Tulis IPPImage.
type: docs
weight: 92
url: /id/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) method


Mengatur gambar untuk objek zoom. Tulis [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Catatan


Contoh ini menunjukkan cara mengubah gambar pada objek Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPPImage](../../ippimage/)
* Kelas [IZoomObject](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)