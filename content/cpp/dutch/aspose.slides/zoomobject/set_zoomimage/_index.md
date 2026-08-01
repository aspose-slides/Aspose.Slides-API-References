---
title: set_ZoomImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de afbeelding in voor het zoomobject. Schrijf IPPImage.
type: docs
weight: 92
url: /nl/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) methode

Stelt de afbeelding in voor het zoomobject. Schrijf [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Opmerkingen

Het voorbeeld toont het wijzigen van een afbeelding van een Zoom-object: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)