---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ – odniesienie API
description: "Ustawia czas trwania przejścia pomiędzy Zoom a slajdem. Zapisz float. Domyślna wartość: 1.0f"
type: docs
weight: 118
url: /pl/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) metoda

Ustawia czas trwania przejścia pomiędzy Zoom a slajdem. Zapisz **float**. Domyślna wartość: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Uwagi

Jeśli nie zostanie określone (TransitionDur = 0), zostanie użyte przejście slajdu docelowego oraz czasy powiązane z tym przejściem. 

przykład pokazuje zmianę czasu trwania przejścia pomiędzy Zoom a slajdem: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Zobacz także

* Klasa [ZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)