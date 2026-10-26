---
title: set_RowGap()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der Wert des vertikalen Abstands zwischen den Zeilen einer Matrix; Wenn die RowGapRule auf 3 (\"Exactly\") gesetzt ist, wird die Einheit als Twips (1/20 eines Punkts) interpretiert. Wenn die RowGapRule auf 4 (\"Multiple\") gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. Standard: 0"
type: docs
weight: 196
url: /de/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) Methode


Der Wert des vertikalen Abstands zwischen den Zeilen einer Matrix; Wenn die RowGapRule auf 3 (\"Exactly\") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die RowGapRule auf 4 (\"Multiple\") gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. Standard: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Bemerkungen


Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Siehe auch

* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)