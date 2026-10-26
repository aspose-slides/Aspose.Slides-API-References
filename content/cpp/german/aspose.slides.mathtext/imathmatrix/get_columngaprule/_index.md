---
title: get_ColumnGapRule()
second_title: Aspose.Slides für C++ API Referenz
description: "Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)"
type: docs
weight: 105
url: /de/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() Methode

Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Anmerkungen

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Siehe auch

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)