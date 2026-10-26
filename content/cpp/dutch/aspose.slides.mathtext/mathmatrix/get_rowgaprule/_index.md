---
title: get_RowGapRule()
second_title: Aspose.Slides voor C++ API-referentie
description: "Het type verticale tussenruimte tussen de rijen van een matrix; verticale tussenruimteenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)"
type: docs
weight: 157
url: /nl/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() methode


Het type verticale tussenruimte tussen rijen van een matrix; verticale tussenruimteenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
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