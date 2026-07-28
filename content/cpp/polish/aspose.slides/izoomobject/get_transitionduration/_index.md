---
title: get_TransitionDuration()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Pobiera czas trwania przejścia między Zoom a slajdem. Odczyt float. Domyślna wartość: 1.0f"
type: docs
weight: 105
url: /pl/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() metoda


Zwraca czas trwania przejścia między Zoom a slajdem. Odczyt **float**. Domyślna wartość: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Uwagi


Jeśli nie określono (TransitionDur = 0), zostanie użyte przejście slajdu docelowego oraz czasy związane z tym przejściem. 

przykład pokazuje zmianę czasu trwania przejścia między Zoom a slajdem: 
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