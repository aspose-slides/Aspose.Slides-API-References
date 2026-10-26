---
title: set_RowGapRule()
second_title: Aspose.Slides für C++ API Referenz
description: "Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)"
type: docs
weight: 170
url: /de/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) Methode


Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; vertikale Abstands-Einheiten können Zeilen oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Anmerkungen


Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Siehe auch

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)