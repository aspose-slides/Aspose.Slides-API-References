---
title: set_RowGapRule()
second_title: Aspose.Slides voor C++ API-referentie
description: "Het type verticale ruimte tussen rijen van een matrix; verticale ruimte-eenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)"
type: docs
weight: 170
url: /nl/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) methode


Het type verticale afstand tussen rijen van een matrix; verticale afstandseenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
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