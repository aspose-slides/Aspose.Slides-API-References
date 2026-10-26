---
title: get_RowGapRule()
second_title: Aspose.Slides för C++ API-referens
description: "Typen av vertikal avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara rader eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)"
type: docs
weight: 157
url: /sv/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() metod


Typen av vertikal avstånd mellan rader i en matris; Vertikala avståndsenheter kan vara rader eller punkter (lagrade som twips). Standard: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Anmärkningar


Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Se även

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klass [IMathMatrix](../)
* Namnutrymme [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)