---
title: get_GridSpacing()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a rácstávolságot, amelyet a prezentációs dokumentum alappontjához kell használni, pontban. Olvasandó float.
type: docs
weight: 92
url: /hu/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() metódus


Visszaadja a rács távolságát, amelyet a prezentációs dokumentum alappontjához kell használni, pontban. Olvasandó **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Megjegyzések


A rács távolság értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

Az alábbi példakód bemutatja, hogyan lehet megváltoztatni a rács távolságát egy PowerPoint-prezentációban.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [ViewProperties](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)