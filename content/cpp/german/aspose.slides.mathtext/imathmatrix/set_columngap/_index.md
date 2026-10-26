---
title: set_ColumnGap()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn die ColumnGapRule auf 3 (\"Exactly\") gesetzt ist, wird die Einheit als twips (1/20 eines Punktes) interpretiert. Wenn die ColumnGapRule auf 4 (\"Multiple\") gesetzt ist, wird die Einheit als Anzahl von 0.5 em Schritten interpretiert. In anderen Fällen ignoriert. Standard: 0"
type: docs
weight: 144
url: /de/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) Methode


Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn die ColumnGapRule auf 3 (\"Exactly\") gesetzt ist, wird die Einheit als twips (1/20 eines Punktes) interpretiert. Wenn die ColumnGapRule auf 4 (\"Multiple\") gesetzt ist, wird die Einheit als Anzahl von 0.5 em Schritten interpretiert. In anderen Fällen ignoriert. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Bemerkungen


Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Siehe auch

* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)