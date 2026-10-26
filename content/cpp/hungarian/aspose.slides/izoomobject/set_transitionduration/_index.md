---
title: set_TransitionDuration()
second_title: Aspose.Slides a C++ API hivatkozás
description: "Beállítja a Zoom és a dia közötti átmenet időtartamát. Írja float típusban. Alapértelmezett érték: 1.0f"
type: docs
weight: 118
url: /hu/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) method

Beállítja a Zoom és a dia közötti átmenet időtartamát. Írja **float**-ként. Alapértelmezett érték: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Megjegyzés

Ha nincs megadva (TransitionDur = 0), akkor a cél dia átmenetét és az ahhoz kapcsolódó időzítéseket fogja használni.

A példa bemutatja a Zoom és a dia közötti átmenet időtartamának módosítását:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Lásd még

* Osztály [IZoomObject](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)