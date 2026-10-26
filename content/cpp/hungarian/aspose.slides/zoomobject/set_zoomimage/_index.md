---
title: set_ZoomImage()
second_title: Aspose.Slides C++ API referencia
description: Beállítja a zoom objektum képét. Írja IPPImage.
type: docs
weight: 92
url: /hu/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) metódus


Beállítja a zoom objektum képét. Írja [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Megjegyzés


A példa bemutatja egy Zoom objektum képének módosítását: 
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