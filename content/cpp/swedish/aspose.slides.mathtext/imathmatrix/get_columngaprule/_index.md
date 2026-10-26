---
title: get_ColumnGapRule()
second_title: Aspose.Slides för C++ API-referens
description: "Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)"
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() metod


Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Anmärkningar


Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Se även

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)