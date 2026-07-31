---
title: get_ZoomImage()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan gambar untuk objek zoom. Baca IPPImage.
type: docs
weight: 79
url: /id/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() metode


Mendapatkan gambar untuk objek zoom. Baca [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Catatan


Contoh ini menunjukkan cara mengubah gambar dari objek Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPPImage](../../ippimage/)
* Kelas [ZoomObject](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)