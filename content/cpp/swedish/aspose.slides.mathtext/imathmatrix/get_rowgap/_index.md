---
title: get_RowGap()
second_title: Aspose.Slides för C++ API-referens
description: "Värdet på vertikalt avstånd mellan rader i en matris; om RowGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) om RowGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som halva rader. Standard: 0"
type: docs
weight: 183
url: /sv/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() metod

Värdet på vertikal avstånd mellan rader i en matris; Om RowGapRule är inställd på 3 ("Exactly") tolkas enheten som twips (1/20 av en punkt) Om RowGapRule är inställd på 4 ("Multiple") tolkas enheten som halva rader. Standard: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Anmärkningar

Exempel:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Se även

* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)