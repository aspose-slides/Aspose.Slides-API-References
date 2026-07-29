---
title: get_ColumnGapRule()
second_title: Aspose.Slides för C++ API-referens
description: "Typen av horisontellt avstånd mellan kolumner i en matris; enheter för horisontellt avstånd kan vara ems eller punkter (lagrade som twip). Standard: SingleSpacingGap (0)"
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() metod


Typen av horisontellt avstånd mellan kolumner i en matris; enheterna för horisontellt avstånd kan vara ems eller punkter (lagrade som twip). Standard: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Anmärkningar


Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Se även

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)