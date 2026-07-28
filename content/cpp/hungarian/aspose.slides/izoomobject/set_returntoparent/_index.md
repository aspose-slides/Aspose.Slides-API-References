---
title: set_ReturnToParent()
second_title: Aspose.Slides C++ API Referencia
description: "Beállítja a navigációs viselkedést a diavetítésben. Írja be a bool értéket. Alapértelmezett érték: false"
type: docs
weight: 40
url: /hu/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) metódus


Állítja a navigációs viselkedést a diavetítésben. Írja be **bool**. Alapértelmezett érték: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Megjegyzések


A tulajdonság igaz értéke határozza meg a szülőhöz való visszatérési navigációs viselkedést a diavetítésben. 

Példa: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Lásd még

* Osztály [IZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)