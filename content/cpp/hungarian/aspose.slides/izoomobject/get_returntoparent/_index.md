---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API referencia
description: "A diavetítésben a navigáció viselkedését adja vissza. Olvasás bool. Alapértelmezett érték: false"
type: docs
weight: 27
url: /hu/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() metódus


A diavetítésben a navigáció viselkedését adja vissza. Olvasás **bool**. Alapértelmezett érték: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Megjegyzés


Az igaz érték azt jelöli, hogy a diavetítésben a szülőhöz való visszatérés navigációs viselkedése legyen.

Példa: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Lásd még

* Osztály [IZoomObject](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)