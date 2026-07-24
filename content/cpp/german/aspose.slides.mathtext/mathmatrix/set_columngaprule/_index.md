---
title: set_ColumnGapRule()
second_title: Aspose.Slides für C++ API Referenz
description: "Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; Horizontale Abstandseinheiten können ems oder Punkte (gespeichert als Twips) sein. Standard: SingleSpacingGap (0)"
type: docs
weight: 118
url: /de/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) Methode

Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; Horizontale Abstandseinheiten können ems oder Punkte (gespeichert als Twips) sein. Standard: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## Hinweise

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Siehe auch

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [MathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)