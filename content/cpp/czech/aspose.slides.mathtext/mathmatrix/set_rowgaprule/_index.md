---
title: set_RowGapRule()
second_title: Aspose.Slides pro C++ API referenci
description: "Typ svislého odsazení mezi řádky matice; jednotky svislého odsazení mohou být řádky nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 170
url: /cs/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) metoda


Typ svislého odsazení mezi řádky matice; jednotky svislého odsazení mohou být řádky nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## Poznámky


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Viz také

* Výčtový typ [MathSpacingRules](../../mathspacingrules/)
* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)