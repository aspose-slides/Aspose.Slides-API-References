---
title: get_ColumnGap()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Hodnota horizontálního odsazení mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 (\"Exactly\"), pak je jednotka interpretována jako twipy (1/20 bodu) pokud je ColumnGapRule nastaven na 4 (\"Multiple\"), pak je jednotka interpretována jako počet kroků po 0,5 em. V ostatních případech je ignorována. Výchozí: 0"
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() metoda

Hodnota horizontálního odsazení mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 ("Exactly"), pak jednotka je interpretována jako twipy (1/20 bodu) pokud je ColumnGapRule nastaven na 4 ("Multiple"), pak jednotka je interpretována jako počet kroků po 0,5 em. V ostatních případech je ignorována. Výchozí: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Poznámky

Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)