---
title: set_RowSpacing()
second_title: Aspose.Slides C++ API referencia
description: "Sorok közti távolság egy tömbben. Csak akkor használatos, ha a RowSpacingRule 3 Exact értékre van állítva, ekkor a mértékegység pont, vagy Multiple esetén a mértékegység fél sor. Alapértelmezett: 0"
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) metódus


Az array sorai közti távolság. Csak akkor használatos, ha a RowSpacingRule 3 Exact értékre van állítva, ekkor a mértékegység pont, vagy Multiple esetén a mértékegység fél sor. Alapértelmezett: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
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