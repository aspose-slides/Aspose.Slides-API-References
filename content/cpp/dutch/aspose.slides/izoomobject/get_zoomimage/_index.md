---
title: get_ZoomImage()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt afbeelding op voor zoomobject. Lees IPPImage.
type: docs
weight: 79
url: /nl/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() methode

Haalt de afbeelding voor het zoomobject op. Lees [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Opmerkingen

Het voorbeeld toont hoe een afbeelding van een Zoom-object te wijzigen:
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