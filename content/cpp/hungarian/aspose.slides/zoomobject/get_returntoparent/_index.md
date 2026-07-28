---
title: get_ReturnToParent()
second_title: Aspose.Slides C++ API referencia
description: "Lekéri a navigációs viselkedést a diavetítésben. Olvasható bool. Alapértelmezett érték: false"
type: docs
weight: 27
url: /hu/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() metódus


Lekéri a navigációs viselkedést a diavetítésben. Olvasható **bool**. Alapértelmezett érték: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Megjegyzések


A tulajdonság true értéke meghatározza a szülőhöz való visszatérés navigációs viselkedését a diavetítésben. 

Példa: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Lásd még

* Osztály [ZoomObject](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)