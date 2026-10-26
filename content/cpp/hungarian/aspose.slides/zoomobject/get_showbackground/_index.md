---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API referencia
description: "Lekéri azt az értéket, amely meghatározza, hogy a Zoom a cél diák háttérképét használja-e. Olvasás bool. Alapértelmezett érték: true"
type: docs
weight: 53
url: /hu/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() metódus


Lekérdezi azt az értéket, amely meghatározza, hogy a Zoom a cél diák háttérképét használja-e. Olvasás **bool**. Alapértelmezett érték: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Megjegyzések


a példa bemutatja egy Zoom objektum képének háttér eltávolítását: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Lásd még

* Osztály [ZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)