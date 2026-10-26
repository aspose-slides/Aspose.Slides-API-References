---
title: get_RowSpacing()
second_title: Aspose.Slides C++ API referenciája
description: "Egy tömb sorai közötti távolság. Csak akkor használatos, ha a RowSpacingRule értéke 3 (Exactly), ekkor a mértékegység pont, vagy ha Multiple, akkor a mértékegység fél sor. Alapértelmezett: 0"
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() metódus

Sorok közötti távolság egy tömbben. Csak akkor használatos, ha a RowSpacingRule értéke 3 (Exactly). Ebben az esetben a mértékegység pont, vagy ha Multiple, akkor a mértékegység fél sor. Default: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Megjegyzések

Példa:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Lásd még

* Osztály [MathArray](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)