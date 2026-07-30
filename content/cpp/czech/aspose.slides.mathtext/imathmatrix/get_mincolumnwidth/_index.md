---
title: get_MinColumnWidth()
second_title: Aspose.Slides pro C++ API Reference
description: "Minimální šířka sloupce v twipsech (1/20 bodu) Mezera mezi sloupci (také nazývaná \\u201CColumn Gap\\u201D nebo \\u201CGap Width\\u201D) se přičítá k MinColumnWidth pro určení celkového rozestupu sloupců v matici (vzdálenost mezi stejnými okraji různých sloupců). Výchozí hodnota: 0."
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() metoda

Minimální šířka sloupce v twipsech (1/20 bodu) Mezery mezi sloupci (také nazývané \\u201CColumn Gap\\u201D nebo \\u201CGap Width\\u201D) se přičítají k MinColumnWidth pro určení celkového Matrix [Column](../../../aspose.slides/column/) Spacing (vzdálenost mezi stejnými okraji různých sloupců). Výchozí hodnota: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## Poznámky

Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)