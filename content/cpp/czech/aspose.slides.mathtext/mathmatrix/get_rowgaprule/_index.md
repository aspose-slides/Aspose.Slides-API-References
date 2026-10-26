---
title: get_RowGapRule()
second_title: Aspose.Slides pro C++ API referencia
description: "Typ vertikálního rozestupu mezi řádky matice; jednotky vertikálního rozestupu mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 157
url: /cs/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() metoda

Typ vertikálního rozestupu mezi řádky matice; jednotky vertikálního rozestupu mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Viz také

* Enum [MathSpacingRules](../../mathspacingrules/)
* třída [MathMatrix](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)