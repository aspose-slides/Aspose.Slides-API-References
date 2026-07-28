---
title: get_TransitionDuration()
second_title: Aspose.Slides C++ API referencia
description: "A Zoom és a dia közötti átmenet időtartamát adja vissza. Olvasás: float. Alapértelmezett érték: 1.0f"
type: docs
weight: 105
url: /hu/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() metódus


A Zoom és a dia közötti átmenet időtartamát adja vissza. Olvasás: **float**. Alapértelmezett érték: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Megjegyzések


Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és az ahhoz tartozó időzítéseket használja. 

A példa bemutatja a Zoom és a dia közötti átmenet időtartamának módosítását: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Lásd még

* Osztály [IZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)