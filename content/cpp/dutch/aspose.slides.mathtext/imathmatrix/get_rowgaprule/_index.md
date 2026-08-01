---
title: get_RowGapRule()
second_title: Aspose.Slides voor C++ API-referentie
description: "Het type verticale spatiëring tussen rijen van een matrix; verticale spatiëringseenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)"
type: docs
weight: 157
url: /nl/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMMathMatrix::get_RowGapRule() methode


Het type verticale spatiëring tussen rijen van een matrix; verticale spatiëringseenheden kunnen regels of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zie ook

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)