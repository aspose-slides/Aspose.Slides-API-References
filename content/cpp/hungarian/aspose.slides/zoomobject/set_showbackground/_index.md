---
title: set_ShowBackground()
second_title: Aspose.Slides C++ API referencia
description: "Beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. Írja bool. Alapértelmezett érték: true"
type: docs
weight: 66
url: /hu/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) metódus

Beállítja azt az értéket, amely meghatározza, hogy a Zoom használja-e a cél dia háttérét. Írja **bool**. Alapértelmezett érték: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Megjegyzések

A példa azt mutatja, hogyan lehet eltávolítani egy Zoom objektum képének háttérét: 
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