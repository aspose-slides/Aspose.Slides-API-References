---
title: get_ColumnGapRule()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte (in Twips gespeichert) sein. Standard: SingleSpacingGap (0)"
type: docs
weight: 105
url: /de/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() Methode


Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte (in Twips gespeichert) sein. Standard: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Anmerkungen


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