---
title: get_RowGap()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Hodnota vertikálního odsazení mezi řádky matice; pokud je RowGapRule nastaven na 3 (\"Exactly\"), jednotka se interpretuje jako twipy (1/20 bodu) pokud je RowGapRule nastaven na 4 (\"Multiple\"), jednotka se interpretuje jako půlřádky. Výchozí: 0"
type: docs
weight: 183
url: /cs/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() metoda


Hodnota vertikálního odsazení mezi řádky matice; pokud je RowGapRule nastaven na 3 (\"Exactly\"), jednotka se interpretuje jako twipy (1/20 bodu) pokud je RowGapRule nastaven na 4 (\"Multiple\"), jednotka se interpretuje jako půlřádky. Výchozí: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Poznámky


Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Viz také

* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)