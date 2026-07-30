---
title: get_TransitionDuration()
second_title: Aspose.Slides pro C++ API Reference
description: "Získá dobu trvání přechodu mezi Zoom a snímkem. Čte float. Výchozí hodnota: 1.0f"
type: docs
weight: 105
url: /cs/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() metoda


Získá dobu trvání přechodu mezi Zoom a snímkem. Čte **float**. Výchozí hodnota: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Poznámky


Pokud není zadáno (TransitionDur = 0), použije se přechod cílového snímku a načasování s ním spojené. 

příklad ukazuje změnu doby trvání přechodu mezi Zoom a snímkem: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Viz také

* Třída [IZoomObject](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)