---
title: get_RowGap()
second_title: Aspose.Slides för C++ API-referens
description: "Värdet för vertikalt avstånd mellan rader i en matris; Om RowGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20th av en punkt) Om RowGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som halvlinjer. Standard: 0"
type: docs
weight: 183
url: /sv/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() metod

Värdet för vertikal avstånd mellan rader i en matris; Om RowGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20th av en punkt) Om RowGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som halvlinjer. Standard: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Anmärkningar

Exempel:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Se även

* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)