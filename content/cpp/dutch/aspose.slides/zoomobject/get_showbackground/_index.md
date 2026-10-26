---
title: get_ShowBackground()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de waarde op die aangeeft of de Zoom de achtergrond van de doel-dia gebruikt. Lees bool. Standaardwaarde: true"
type: docs
weight: 53
url: /nl/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() methode

Haalt de waarde op die aangeeft of de Zoom de achtergrond van de doel-dia gebruikt. Lees **bool**. Standaardwaarde: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Opmerkingen

Het voorbeeld toont het verwijderen van de achtergrond van een afbeelding van een Zoom-object:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Zie ook

* Klasse [ZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)