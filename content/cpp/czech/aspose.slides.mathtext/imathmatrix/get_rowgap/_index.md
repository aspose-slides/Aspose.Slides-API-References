---
title: get_RowGap()
second_title: Aspose.Slides pro C++ API Reference
description: "Hodnota vertikálního odsazení mezi řádky matice; pokud je RowGapRule nastaven na 3 (\"Exactly\"), jednotka se interpretuje jako twips (1/20 bodu) pokud je RowGapRule nastaven na 4 (\"Multiple\"), jednotka se interpretuje jako půlčáry. Výchozí: 0"
type: docs
weight: 183
url: /cs/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() metoda

Hodnota svislého odsazení mezi řádky matice; pokud je RowGapRule nastaven na 3 (\"Exactly\"), jednotka se interpretuje jako twips (1/20 bodu) pokud je RowGapRule nastaven na 4 (\"Multiple\"), jednotka se interpretuje jako půlčáry. Výchozí: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Poznámky

Příklad: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Viz také

* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)