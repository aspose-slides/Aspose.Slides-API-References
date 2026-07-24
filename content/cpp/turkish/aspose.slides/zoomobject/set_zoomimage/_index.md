---
title: set_ZoomImage()
second_title: Aspose.Slides için C++ API Referansı
description: Zoom nesnesi için resmi ayarlar. IPPImage'i yazın.
type: docs
weight: 92
url: /tr/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metot


Zoom nesnesi için resmi ayarlar. Yazın [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Açıklamalar


Örnek, bir Zoom nesnesinin resmini değiştirmeyi gösterir: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)