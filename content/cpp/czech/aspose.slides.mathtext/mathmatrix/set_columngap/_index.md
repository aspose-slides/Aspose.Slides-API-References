---
title: set_ColumnGap()
second_title: Aspose.Slides pro C++ API Reference
description: "Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 (\"Exactly\"), jednotka se interpretuje jako twipy (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 (\"Multiple\"), jednotka se interpretuje jako počet kroků po 0,5 em. V ostatních případech je ignorována. Výchozí hodnota: 0"
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) method


Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 (\"Exactly\"), jednotka se interpretuje jako twipy (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 (\"Multiple\"), jednotka se interpretuje jako počet kroků po 0.5 em. V ostatních případech je ignorována. Výchozí hodnota: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## Remarks


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## See Also

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)