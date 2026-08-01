---
title: get_ShowBackground()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de waarde op die aangeeft of de Zoom de achtergrond van de doeldia zal gebruiken. Lezen bool. Standaardwaarde: true"
type: docs
weight: 53
url: /nl/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() methode

Haalt de waarde op die aangeeft of de Zoom de achtergrond van de doeldia zal gebruiken. Lezen **bool**. Standaardwaarde: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
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

* Klasse [IZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)