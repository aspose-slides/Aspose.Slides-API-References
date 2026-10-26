---
title: set_TransitionDuration()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Nastaví dobu trvání přechodu mezi Zoom a snímkem. Zapište float. Výchozí hodnota: 1.0f"
type: docs
weight: 118
url: /cs/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) metoda

Nastaví dobu trvání přechodu mezi Zoom a snímkem. Zapište **float**. Výchozí hodnota: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Poznámky

Pokud není specifikováno (TransitionDur = 0), bude použita přechodová animace cílového snímku a časování s ním spojené.

Příklad ukazuje změnu doby trvání přechodu mezi Zoom a snímkem:
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