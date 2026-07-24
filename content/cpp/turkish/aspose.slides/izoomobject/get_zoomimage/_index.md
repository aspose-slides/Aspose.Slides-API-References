---
title: get_ZoomImage()
second_title: Aspose.Slides için C++ API Referansı
description: Zoom nesnesi için resmi alır. IPPImage'ı okuyun.
type: docs
weight: 79
url: /tr/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() method


Zoom nesnesi için resmi alır. [IPPImage](../../ippimage/)'i okuyun.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Remarks


Örnek, bir Zoom nesnesinin resmini değiştirmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPPImage](../../ippimage/)
* Sınıf [IZoomObject](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)