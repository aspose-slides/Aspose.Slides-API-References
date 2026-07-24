---
title: set_ZoomImage()
second_title: Aspose.Slides için C++ API Referansı
description: Zoom nesnesi için resmi ayarlar. IPPImage yazın.
type: docs
weight: 92
url: /tr/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metodu

Zoom nesnesi için resmi ayarlar. [IPPImage](../../ippimage/) yazın.

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Açıklamalar

Bu örnek, bir Zoom nesnesinin resmini değiştirmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [IZoomObject](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)