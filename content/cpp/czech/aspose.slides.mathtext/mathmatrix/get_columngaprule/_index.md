---
title: get_ColumnGapRule()
second_title: Aspose.Slides pro C++ API reference
description: "Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být em nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() metoda


Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být em nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Poznámky


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Viz také

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)