---
title: get_GridSpacing()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de rasterafstand die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. Lees float.
type: docs
weight: 92
url: /nl/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() methode

Retourneert de rasterafstand die moet worden gebruikt voor het raster dat ten grondslag ligt aan het presentatiedocument, in punten. Lezen **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Opmerkingen

De rasterafstandwaarde moet een positief getal zijn. Het typische waardebereik ligt tussen 1 mm (2.8349607 punten) en 2 inches (144 punten).

De onderstaande voorbeeldcode laat zien hoe u de rasterafstand in een PowerPoint-presentatie wijzigt. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IViewProperties](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)