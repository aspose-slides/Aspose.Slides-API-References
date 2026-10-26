---
title: set_ColumnGapRule()
second_title: Aspose.Slides pro C++ API Reference
description: "Typ horizontálního odsazení mezi sloupci matice; jednotky horizontálního odsazení mohou být ems nebo points (uloženy jako twips). Výchozí: SingleSpacingGap (0)"
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) metoda

Typ horizontálního odsazení mezi sloupci matice; jednotky horizontálního odsazení mohou být ems nebo points (uloženy jako twips). Výchozí: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
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