---
title: set_ColumnGapRule()
second_title: Aspose.Slides för C++ API-referens
description: "Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)"
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) metod


Typen av horisontellt avstånd mellan kolumner i en matris; Horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
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