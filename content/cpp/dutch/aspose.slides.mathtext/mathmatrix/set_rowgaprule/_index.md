---
title: set_RowGapRule()
second_title: Aspose.Slides voor C++ API-referentie
description: "Het type verticale tussenruimte tussen rijen van een matrix; verticale tussenruimeenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)"
type: docs
weight: 170
url: /nl/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) methode

Het type verticale tussenruimte tussen rijen van een matrix; verticale tussenruimeenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zie ook

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)