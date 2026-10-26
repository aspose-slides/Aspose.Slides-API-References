---
title: get_ColumnGapRule()
second_title: Aspose.Slides pro C++ API Reference
description: "Typ horizontálního odsazení mezi sloupci matice; jednotky horizontálního odsazení mohou být ems nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() metoda


Typ horizontálního odsazení mezi sloupci matice; Jednotky horizontálního odsazení mohou být ems nebo body (uloženy jako twips). Default: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Poznámky


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Viz také

* Enum [MathSpacingRules](../../mathspacingrules/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)