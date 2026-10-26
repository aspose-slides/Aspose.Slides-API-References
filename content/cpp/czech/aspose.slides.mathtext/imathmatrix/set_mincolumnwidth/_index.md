---
title: set_MinColumnWidth()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Minimální šířka sloupce v twips (1/20 bodu) Vzdálenost mezery (také nazývaná \\u201CColumn Gap\\u201D nebo \\u201CGap Width\\u201D) se přičítá k MinColumnWidth pro určení celkové mezery Matrix Column (vzdálenost mezi stejnými hranami různých sloupců). Výchozí hodnota: 0."
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) metoda

Minimální šířka sloupce v twips (1/20 bodu). Vzdálenost mezery (také označovaná jako \u201CColumn Gap\u201D nebo \u201CGap Width\u201D) se přičítá k MinColumnWidth pro určení celkové mezery Matrix [Column](../../../aspose.slides/column/) (vzdálenost mezi stejnými hranami různých sloupců). Výchozí hodnota: 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
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