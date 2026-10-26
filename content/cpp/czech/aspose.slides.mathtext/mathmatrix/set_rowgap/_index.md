---
title: set_RowGap()
second_title: Aspose.Slides pro C++ API Reference
description: "Hodnota svislého rozestupu mezi řádky matice; Pokud je RowGapRule nastaven na 3 (\"Exactly\"), pak je jednotka interpretována jako twipy (1/20 bodu) Pokud je RowGapRule nastaven na 4 (\"Multiple\"), pak je jednotka interpretována jako půlřádky. Výchozí: 0"
type: docs
weight: 196
url: /cs/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) metoda

Hodnota svislého rozestupu mezi řádky matice; pokud je RowGapRule nastaven na 3 ("Exactly"), pak je jednotka interpretována jako twip (1/20 bodu) pokud je RowGapRule nastaven na 4 ("Multiple"), pak je jednotka interpretována jako půlřádky. Výchozí: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
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