---
title: set_RowGap()
second_title: Aspose.Slides för C++ API-referens
description: "Värdet för vertikal avstånd mellan rader i en matris; om RowGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) om RowGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som halva rader. Standard: 0"
type: docs
weight: 196
url: /sv/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) metod

Värdet för vertikal avstånd mellan rader i en matris; om RowGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) om RowGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som halva rader. Standard: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## Anmärkningar

Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Se också

* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)