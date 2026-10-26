---
title: set_ColumnGapRule()
second_title: Aspose.Slides pro C++ API Reference
description: "Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být em nebo body (uloženy jako twipy). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) metoda


Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být em nebo body (uloženy jako twipy). Výchozí: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## Poznámky


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Viz také

* Výčet [MathSpacingRules](../../mathspacingrules/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)