---
title: set_ZoomImage()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in bild för zoom-objektet. Skriv IPPImage.
type: docs
weight: 92
url: /sv/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metod

Ställer in bild för zoom-objektet. Skriv [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Anmärkningar

Exemplet visar hur man ändrar en bild för ett Zoom-objekt:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IPPImage](../../ippimage/)
* klass [IZoomObject](../)
* namnrymd [Aspose::Slides](../../)
* bibliotek [Aspose.Slides](../../../)