---
title: get_TransitionDuration()
second_title: Aspose.Slides pro C++ reference API
description: "Získá dobu trvání přechodu mezi Zoom a snímkem. Čte float. Výchozí hodnota: 1.0f"
type: docs
weight: 105
url: /cs/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() metoda

Získá dobu trvání přechodu mezi Zoom a snímkem. Čte **float**. Výchozí hodnota: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Poznámky

Pokud není specifikováno (TransitionDur = 0), použije se přechod cílového snímku a časování s ním spojené.

příklad ukazuje změnu doby trvání přechodu mezi Zoom a snímkem:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Viz také

* Třída [ZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)