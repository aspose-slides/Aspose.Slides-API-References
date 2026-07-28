---
title: set_ShowBackground()
second_title: Aspose.Slides C++ API hivatkozás
description: "Beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Írja bool. Alapértelmezett érték: true"
type: docs
weight: 66
url: /hu/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) metódus

Beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél diát háttérként. Írja **bool**. Alapértelmezett érték: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Megjegyzések

A példa bemutatja egy Zoom objektum képének háttér eltávolítását:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Lásd még

* Osztály [IZoomObject](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)