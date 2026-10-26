---
title: get_ShowBackground()
second_title: Aspose.Slides C++ API referencia
description: "Visszaadja azt az értéket, amely meghatározza, hogy a Zoom a céldiap hátterét használja-e. Olvas bool. Alapértelmezett érték: true"
type: docs
weight: 53
url: /hu/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() metódus


Érték, amely meghatározza, hogy a Zoom a céldiapozitív háttérét használja-e. Olvas **bool**. Alapértelmezett érték: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Megjegyzések


A példa bemutatja egy Zoom objektum képe háttérének eltávolítását: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Lásd még

* Osztály [IZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)