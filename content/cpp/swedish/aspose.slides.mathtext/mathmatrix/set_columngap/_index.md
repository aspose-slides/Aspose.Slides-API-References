---
title: set_ColumnGap()
second_title: Aspose.Slides för C++ API-referens
description: "Värdet för horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) Om ColumnGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som antal 0,5 em-ökningar. I andra fall ignoreras det. Standard: 0"
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) metod


Värdet för horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) Om ColumnGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som antal 0,5 em-ökningar. I andra fall ignoreras det. Standard: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## Anmärkningar


Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Se även

* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)