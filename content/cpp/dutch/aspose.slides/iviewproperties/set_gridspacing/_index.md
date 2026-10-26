---
title: set_GridSpacing()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Schrijf float.
type: docs
weight: 105
url: /nl/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) methode

Stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Schrijf **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Opmerkingen

De rasterafstandwaarde moet een positief getal zijn. Het typische waardebereik is van 1 mm (2.8349607 punten) tot 2 inch (144 punten).

De volgende voorbeeldcode laat zien hoe de rasterafstand in een PowerPoint-presentatie kan worden gewijzigd. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IViewProperties](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)