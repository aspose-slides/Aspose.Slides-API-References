---
title: set_TransitionDuration()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Ustawia czas trwania przejścia między Zoom a slajdem. Zapisz float. Wartość domyślna: 1.0f"
type: docs
weight: 118
url: /pl/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) metoda


Ustawia czas trwania przejścia między Zoom a slajdem. Zapisz **float**. Wartość domyślna: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Uwagi


Jeśli nie zostanie określone (TransitionDur = 0), zostanie użyte przejście slajdu docelowego oraz czasy związane z tym przejściem. 

Przykład pokazuje zmianę czasu trwania przejścia między Zoom a slajdem: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Zobacz także

* Klasa [IZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)