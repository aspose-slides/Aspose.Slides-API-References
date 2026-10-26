---
title: set_GridSpacing()
second_title: Aspose.Slides C++ API Referenciája
description: Beállítja a rácstávolságot, amelyet a prezentációs dokumentum alá tartozó rács használ, pontokban. Írja float.
type: docs
weight: 105
url: /hu/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) metódus

Beállítja a rácstávolságot, amelyet a prezentációs dokumentum alá tartozó rács használ, pontokban. Írja **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Megjegyzések

A rácstávolság értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

Az alábbi példakód bemutatja, hogyan lehet megváltoztatni a rácstávolságot egy PowerPoint prezentációban.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IViewProperties](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)