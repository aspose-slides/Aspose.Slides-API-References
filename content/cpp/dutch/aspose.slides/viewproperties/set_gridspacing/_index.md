---
title: set_GridSpacing()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Schrijf float.
type: docs
weight: 105
url: /nl/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) methode


Stelt de rasterafstand in die moet worden gebruikt voor het raster onderliggend aan het presentatiedocument, in punten. Schrijf **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Opmerkingen


De rasterafstandwaarde moet een positief getal zijn. Het typische bereik ligt tussen 1 mm (2.8349607 punten) en 2 inch (144 punten). 

De volgende voorbeeldcode laat zien hoe u de rasterafstand wijzigt in een PowerPoint-presentatie. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [ViewProperties](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)