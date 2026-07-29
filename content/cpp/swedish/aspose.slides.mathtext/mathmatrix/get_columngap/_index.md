---
title: get_ColumnGap()
second_title: Aspose.Slides för C++ API-referens
description: "Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) Om ColumnGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som antalet 0.5 em-ökningar. I andra fall ignoreras det. Standard: 0"
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() metod


Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är inställd på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) Om ColumnGapRule är inställd på 4 (\"Multiple\"), tolkas enheten som antal 0,5 em-ökningar. I andra fall ignoreras det. Standard: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
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