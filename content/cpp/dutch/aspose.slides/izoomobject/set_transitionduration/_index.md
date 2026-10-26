---
title: set_TransitionDuration()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de duur van de overgang tussen Zoom en dia in. Schrijf float. Standaardwaarde: 1.0f"
type: docs
weight: 118
url: /nl/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) methode


Stelt de duur van de overgang tussen Zoom en dia in. Schrijf **float**. Standaardwaarde: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Opmerkingen


Indien niet gespecificeerd (TransitionDur = 0), wordt de overgang van de doeldia gebruikt en de timing die aan die overgang is gekoppeld. 

het voorbeeld toont het wijzigen van de duur van de overgang tussen Zoom en dia: 
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