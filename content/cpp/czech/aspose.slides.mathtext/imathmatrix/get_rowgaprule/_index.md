---
title: get_RowGapRule()
second_title: Aspose.Slides pro C++ API Reference
description: "Typ vertikálního odsazení mezi řádky matice; jednotky vertikálního odsazení mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 157
url: /cs/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() metoda

Typ vertikálního odsazení mezi řádky matice; jednotky vertikálního odsazení mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Viz také

* Výčet [MathSpacingRules](../../mathspacingrules/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)