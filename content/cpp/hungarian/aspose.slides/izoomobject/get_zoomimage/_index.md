---
title: get_ZoomImage()
second_title: Aspose.Slides C++ API-referencia
description: Képet kér a zoom objektumhoz. Olvassa el az IPPImage-et.
type: docs
weight: 79
url: /hu/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() method

Képet kér a Zoom objektumhoz. Olvassa el [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Megjegyzések

A példa bemutatja a Zoom objektum képének módosítását: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPPImage](../../ippimage/)
* Osztály [IZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)