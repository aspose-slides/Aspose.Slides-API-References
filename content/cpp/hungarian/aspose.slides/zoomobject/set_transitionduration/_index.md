---
title: set_TransitionDuration()
second_title: Aspose.Slides for C++ API Referencia
description: "Beállítja a Zoom és a dia közötti átmenet időtartamát. Írja float. Alapértelmezett érték: 1.0f"
type: docs
weight: 118
url: /hu/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) metódus


Beállítja a Zoom és a dia közötti átmenet időtartamát. Írja **float**. Alapértelmezett érték: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Megjegyzések


Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és az ahhoz kapcsolódó időzítéseket használja.  

A példa bemutatja a Zoom és a dia közötti átmenet időtartamának módosítását: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Lásd még

* Osztály [ZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)