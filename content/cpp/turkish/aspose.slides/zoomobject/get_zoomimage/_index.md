---
title: get_ZoomImage()
second_title: Aspose.Slides for C++ API Referansı
description: Yakınlaştırma nesnesi için resmi alır. IPPImage okuyun.
type: docs
weight: 79
url: /tr/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() metodu

Yakınlaştırma nesnesi için resmi alır. [IPPImage](../../ippimage/) okuyun.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Açıklamalar

Örnek, bir Zoom nesnesinin resmini değiştirmenin nasıl yapılacağını gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [ZoomObject](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)