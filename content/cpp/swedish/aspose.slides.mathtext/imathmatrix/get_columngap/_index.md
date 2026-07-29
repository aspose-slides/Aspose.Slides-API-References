---
title: get_ColumnGap()
second_title: Aspose.Slides för C++ API-referens
description: "Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är inställt på 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt) Om ColumnGapRule är inställt på 4 (\"Multiple\"), tolkas enheten som antal 0.5 em-steg. I andra fall ignoreras det. Standard: 0"
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() metod


Värdet på horisontellt avstånd mellan kolumner i en matris; Om ColumnGapRule är inställd på 3 ("Exactly"), tolkas enheten som twips (1/20 av en punkt) Om ColumnGapRule är inställd på 4 ("Multiple"), tolkas enheten som antal 0,5 em-steg. I andra fall ignoreras det. Standard: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Anmärkningar


Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Se även

* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)