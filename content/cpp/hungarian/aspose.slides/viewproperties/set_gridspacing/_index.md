---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API referencia
description: Beállítja a rács térközét, amelyet a prezentációs dokumentum alatti rácshoz kell használni, pontban. Írja float.
type: docs
weight: 105
url: /hu/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) metódus


Beállítja a rács térközét, amelyet a prezentációs dokumentum alatti rácshoz kell használni, pontban. Írja **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Megjegyzés


A rács térköz értékének pozitív számnak kell lennie. A tipikus értéktartomány 1 mm (2.8349607 pont) és 2 hüvelyk (144 pont) között.

Az alábbi mintakód megmutatja, hogyan lehet módosítani a rács térközét egy PowerPoint-prezentációban. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [ViewProperties](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)