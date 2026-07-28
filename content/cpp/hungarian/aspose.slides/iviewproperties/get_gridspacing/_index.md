---
title: get_GridSpacing()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a rácstávolságot, amelyet a prezentációs dokumentum alá tartozó rácshoz kell használni, pontban. Olvasás float.
type: docs
weight: 92
url: /hu/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() metódus

Visszaadja a rácstávolságot, amelyet a prezentációs dokumentum alá tartozó rácshoz kell használni, pontban. Olvasás **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Megjegyzések

A rácstávolság értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

Az alábbi minta kód bemutatja, hogyan lehet megváltoztatni a rácstávolságot egy PowerPoint-prezentációban. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IViewProperties](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)