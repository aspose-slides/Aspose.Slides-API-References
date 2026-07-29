---
title: get_ZoomImage()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar bild för zoom-objektet. Läs IPPImage.
type: docs
weight: 79
url: /sv/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() metod

Hämtar bild för zoom-objektet. Läs [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
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

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IPPImage](../../ippimage/)
* Klass [ZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)