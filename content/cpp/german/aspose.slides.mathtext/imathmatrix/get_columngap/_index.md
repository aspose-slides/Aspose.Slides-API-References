---
title: get_ColumnGap()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der Wert des horizontalen Abstands zwischen den Spalten einer Matrix; Wenn die ColumnGapRule auf 3 (\"Exactly\") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die ColumnGapRule auf 4 (\"Multiple\") gesetzt ist, wird die Einheit als Anzahl von 0.5 em Schritten interpretiert. In anderen Fällen wird sie ignoriert. Standard: 0"
type: docs
weight: 131
url: /de/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() Methode

Der Wert des horizontalen Abstands zwischen den Spalten einer Matrix; Wenn die ColumnGapRule auf 3 ("Exactly") eingestellt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die ColumnGapRule auf 4 ("Multiple") eingestellt ist, wird die Einheit als Anzahl von 0.5 em Schritten interpretiert. In anderen Fällen wird sie ignoriert. Standard: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Anmerkungen

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