---
title: get_ZoomImage()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar bild för zoom-objektet. Läs IPPImage.
type: docs
weight: 79
url: /sv/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() metod

Hämtar bild för zoom-objektet. Läs [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Anmärkningar

Exemplet visar hur man byter bild på ett Zoom-objekt: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPPImage](../../ippimage/)
* Klass [IZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)