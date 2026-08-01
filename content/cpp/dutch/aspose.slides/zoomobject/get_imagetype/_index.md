---
title: get_ImageType()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt het afbeeldingstype op van een zoomobject. Lees ZoomImageType. Standaardwaarde: Preview"
type: docs
weight: 1
url: /nl/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() methode

Verkrijgt het afbeeldingstype van een zoomobject. Lees [ZoomImageType](../../zoomimagetype/). Standaardwaarde: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Opmerkingen

Geeft aan of het Zoom-object de slide-preview of een omslagafbeelding gebruikt.

Het volgende voorbeeld toont het wijzigen van Image Type naar de waarde Preview. In dit geval verandert de huidige afbeelding van een Zoom-object naar de slide-afbeelding: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Zie ook

* Enum [ZoomImageType](../../zoomimagetype/)
* Klasse [ZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)