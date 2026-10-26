---
title: get_ZoomImage()
second_title: Aspose.Slides C++ API referencia
description: Lekérdezi a zoom objektum képét. Olvassa el az IPPImage-et.
type: docs
weight: 79
url: /hu/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() metódus


Lekérdezi a zoom objektum képét. Olvasd el [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Megjegyzések


A példa bemutatja egy Zoom objektum képének megváltoztatását: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPPImage](../../ippimage/)
* Osztály [ZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)