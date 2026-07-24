---
title: get_RowGapRule()
second_title: Aspose.Slides für C++ API-Referenz
description: "Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0)"
type: docs
weight: 157
url: /de/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() Methode

Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Anmerkungen

Beispiel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Siehe auch

* Aufzählung [MathSpacingRules](../../mathspacingrules/)
* Klasse [IMathMatrix](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)