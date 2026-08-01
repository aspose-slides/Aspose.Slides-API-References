---
title: get_GridSpacing()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de rasterafstand terug die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. Lees float.
type: docs
weight: 92
url: /nl/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() methode

Geeft de rasterafstand terug die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. Lees **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Opmerkingen

De waarde van de rasterafstand moet een positief getal zijn. Het typische waardenbereik loopt van 1 mm (2.8349607 punten) tot 2 inch (144 punten).

De volgende voorbeeldcode toont hoe de rasterafstand in een PowerPoint-presentatie kan worden gewijzigd. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [ViewProperties](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)