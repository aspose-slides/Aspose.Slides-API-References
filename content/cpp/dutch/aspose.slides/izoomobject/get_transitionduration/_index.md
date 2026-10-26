---
title: get_TransitionDuration()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt de duur van de overgang tussen Zoom en dia op. Lezen float. Standaardwaarde: 1.0f"
type: docs
weight: 105
url: /nl/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() methode


Haalt de duur van de overgang tussen Zoom en dia op. Lezen **float**. Standaardwaarde: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Opmerkingen


Indien niet gespecificeerd (TransitionDur = 0), wordt de overgang van de doel-diat gebruikt samen met de tijdschema's die aan die overgang gekoppeld zijn. 

Het voorbeeld toont hoe de duur van de overgang tussen Zoom en dia kan worden gewijzigd: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Zie ook

* Klasse [IZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)