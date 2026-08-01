---
title: set_ZoomImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt afbeelding in voor zoomobject. Schrijf IPPImage.
type: docs
weight: 92
url: /nl/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) methode


Stelt afbeelding in voor zoomobject. Schrijf [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Opmerkingen


Het voorbeeld laat zien hoe je een afbeelding van een Zoom-object wijzigt: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)