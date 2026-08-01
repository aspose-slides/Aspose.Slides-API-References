---
title: set_ImageType()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het afbeeldingstype van een zoomobject in. Schrijf ZoomImageType. Standaardwaarde: Preview"
type: docs
weight: 14
url: /nl/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) methode


Stelt het afbeeldingstype van een zoomobject in. Schrijf [ZoomImageType](../../zoomimagetype/). Standaardwaarde: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Opmerkingen


Bepaalt of het Zoom-object de dia-preview of een omslagafbeelding gebruikt.

Dit voorbeeld toont het wijzigen van Image Type naar de preview-waarde. In dit geval verandert de huidige afbeelding van een Zoom-object naar de dia-afbeelding: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Zie ook

* Enum [ZoomImageType](../../zoomimagetype/)
* Klasse [IZoomObject](../)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)