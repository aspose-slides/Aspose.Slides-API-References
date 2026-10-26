---
title: set_ColumnGap()
second_title: Aspose.Slides pro C++ API Reference
description: "Hodnota vodorovného odstupu mezi sloupci matice; pokud je ColumnGapRule nastavena na 3 (\"Exactly\"), pak se jednotka interpretuje jako twip (1/20 bodu) pokud je ColumnGapRule nastavena na 4 (\"Multiple\"), pak se jednotka interpretuje jako počet 0.5 em kroků. V ostatních případech je ignorována. Výchozí: 0"
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) metoda

Hodnota vodorovného odstupu mezi sloupci matice; pokud je ColumnGapRule nastavena na 3 ("Exactly"), pak se jednotka interpretuje jako twip (1/20 bodu). Pokud je ColumnGapRule nastavena na 4 ("Multiple"), pak se jednotka interpretuje jako počet 0.5 em kroků. V ostatních případech je ignorována. Výchozí: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
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