---
title: get_TransitionDuration()
second_title: Aspose.Slides C++ API referencia
description: "A Zoom és a dia közötti átmenet időtartamát adja vissza. Olvasható float. Alapértelmezett érték: 1.0f"
type: docs
weight: 105
url: /hu/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() metódus

A Zoom és a diák közötti átmenet időtartamát adja vissza. Olvasható **float**. Alapértelmezett érték: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
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
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)