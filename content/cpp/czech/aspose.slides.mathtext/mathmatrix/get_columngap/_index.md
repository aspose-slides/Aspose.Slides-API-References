---
title: get_ColumnGap()
second_title: Aspose.Slides pro C++ referenční příručku API
description: "Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 (\"Exactly\"), jednotka se interpretuje jako twips (1/20 bodu) pokud je ColumnGapRule nastaven na 4 (\"Multiple\"), jednotka se interpretuje jako počet kroků po 0,5 em. V ostatních případech se ignoruje. Výchozí: 0"
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() metoda

Hodnota vodorovného odsazení mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka se interpretuje jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka se interpretuje jako počet kroků po 0,5 em. V ostatních případech se ignoruje. Výchozí: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)