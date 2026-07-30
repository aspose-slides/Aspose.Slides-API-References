---
title: set_RowGapRule()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být řádky nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 170
url: /cs/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) metoda


Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být řádky nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Poznámky


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Viz také

* Enum [MathSpacingRules](../../mathspacingrules/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)