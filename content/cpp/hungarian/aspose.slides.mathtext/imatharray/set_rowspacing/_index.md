---
title: set_RowSpacing()
second_title: Aspose.Slides C++ API hivatkozás
description: "A tömb sorai közötti távolság. Csak akkor használható, ha a RowSpacingRule 3-ra van állítva. Ebben az esetben a mérőegység pont, vagy ha Multiple van beállítva, akkor a mérőegység fél sor. Alapértelmezett: 0"
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) metódus


A tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule 3-ra van állítva, ekkor a mérőegység pont, vagy ha Multiple-ra van állítva, ekkor a mérőegység fél sor. Alapértelmezett: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Megjegyzések


Példa: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Lásd még

* Osztály [IMathArray](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)