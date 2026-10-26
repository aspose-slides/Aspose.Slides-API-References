---
title: get_ImageType()
second_title: Aspose.Slides voor C++ API Referentie
description: "Haalt het beeldtype van een zoomobject op. Lees ZoomImageType. Standaardwaarde: Preview"
type: docs
weight: 1
url: /nl/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() methode


Haalt het beeldtype van een zoomobject op. Lees [ZoomImageType](../../zoomimagetype/). Standaardwaarde: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Opmerkingen


Specificeert of het Zoom-object de dia-preview of een omslagafbeelding gebruikt. 

Dit voorbeeld toont het wijzigen van Image Type naar de Preview-waarde. In dit geval verandert de huidige afbeelding van een Zoom-object naar de dia-afbeelding: 
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
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)