---
title: get_TransitionDuration()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de duur van de overgang tussen Zoom en dia op. Lees float. Standaardwaarde: 1.0f"
type: docs
weight: 105
url: /nl/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() methode

Haalt de duur van de overgang tussen Zoom en dia op. Lees **float**. Standaardwaarde: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Opmerkingen

Indien niet gespecificeerd (TransitionDur = 0), wordt de overgang van de bestemmingsdia gebruikt en de tijden die bij die overgang horen.

Het voorbeeld toont het wijzigen van de duur van de overgang tussen Zoom en dia: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Zie ook

* Klasse [ZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)