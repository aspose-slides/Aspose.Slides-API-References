---
title: get_BaseJustification()
second_title: Aspose.Slides C++ API referenciája
description: "Meghatározza a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom és center. Alapértelmezett: Center"
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() metódus


Meghatározza a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom és center. Alapértelmezett: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Megjegyzések


Példa: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Lásd még

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Osztály [IMathMatrix](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)