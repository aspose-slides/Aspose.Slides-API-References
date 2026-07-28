---
title: get_BaseJustification()
second_title: Aspose.Slides C++ API referencia
description: "Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom és center. Alapértelmezett: Center"
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() metódus

Meghatározza a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom és center. Alapértelmezett: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## Megjegyzések

Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Lásd még

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Osztály [MathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)