---
title: get_RowSpacing()
second_title: Aspose.Slides C++ API referenciája
description: "A tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule értéke 3 pontos, ebben az esetben a mértékegység pont, vagy ha Multiple, ebben az esetben a mértékegység fél sor. Alapértelmezett: 0"
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() metódus


Az tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule értéke 3 pontosan, ebben az esetben a mértékegység pont, vagy ha Multiple, ebben az esetben a mértékegység fél sor. Alapértelmezett: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
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