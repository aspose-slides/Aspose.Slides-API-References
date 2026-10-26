---
title: set_RowGapRule()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte sein (als Twips gespeichert). Standard: SingleSpacingGap (0)"
type: docs
weight: 170
url: /de/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) Methode


Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; Vertikale Abstandseinheiten können Zeilen oder Punkte sein (als Twips gespeichert). Standard: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## Bemerkungen


Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Siehe auch

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)