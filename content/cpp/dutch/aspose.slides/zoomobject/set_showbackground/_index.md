---
title: set_ShowBackground()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken. Schrijf bool. Standaardwaarde: true"
type: docs
weight: 66
url: /nl/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) methode

Stelt de waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken. Schrijf **bool**. Standaardwaarde: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Opmerkingen

Het voorbeeld laat zien hoe de achtergrond van een afbeelding van een Zoom-object wordt verwijderd:
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