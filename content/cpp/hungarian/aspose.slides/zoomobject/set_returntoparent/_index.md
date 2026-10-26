---
title: set_ReturnToParent()
second_title: Aspose.Slides C++ API Referencia
description: "Beállítja a navigációs viselkedést a diavetítésben. Írja bool. Alapértelmezett érték: false"
type: docs
weight: 40
url: /hu/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) method

Beállítja a navigációs viselkedést a diavetítésben. Írja **bool**. Alapértelmezett érték: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Remarks

A tulajdonság true értéke határozza meg a szülőhöz való visszatérés navigációs viselkedését a diavetítésben. 

Példa: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Lásd még

* Osztály [ZoomObject](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)