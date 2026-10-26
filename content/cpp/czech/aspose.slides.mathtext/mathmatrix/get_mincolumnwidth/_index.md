---
title: get_MinColumnWidth()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Minimální šířka sloupce v twips (1/20 bodu) Mezerní mezera (také nazývaná \\u201CColumn Gap\\u201D nebo \\u201CGap Width\\u201D) se přidá k MinColumnWidth pro určení celkového odsazení sloupců v matici (vzdálenost mezi stejnými okraji různých sloupců). Výchozí: 0."
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() metoda

Minimální šířka sloupce v twips (1/20 bodu) Mezerní vzdálenost (také nazývaná „Column Gap“ nebo „Gap Width“) se přidá k MinColumnWidth pro určení celkové Matrix [Column](../../../aspose.slides/column/) Spacing (vzdálenost mezi stejnými okraji různých sloupců). Výchozí: 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
```

## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)