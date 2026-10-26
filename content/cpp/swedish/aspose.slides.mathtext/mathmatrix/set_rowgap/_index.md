---
title: set_RowGap()
second_title: Aspose.Slides för C++ API-referens
description: "Värdet för vertikal avstånd mellan rader i en matris; Om RowGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) Om RowGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som halva rader. Standard: 0"
type: docs
weight: 196
url: /sv/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) metod

Värdet för vertikal avstånd mellan rader i en matris; Om RowGapRule är inställd på 3 ("Exactly"), tolkas enheten som twips (1/20 av en punkt) Om RowGapRule är inställd på 4 ("Multiple"), tolkas enheten som halva rader. Standard: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
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
* Library [Aspose.Slides](../../../)