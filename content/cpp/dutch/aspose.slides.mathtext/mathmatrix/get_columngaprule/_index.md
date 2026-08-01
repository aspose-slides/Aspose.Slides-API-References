---
title: get_ColumnGapRule()
second_title: Aspose.Slides voor C++ API-referentie
description: "Het type horizontale afstand tussen kolommen van een matrix; horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)"
type: docs
weight: 105
url: /nl/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() methode


Het type horizontale afstand tussen kolommen van een matrix; horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zie ook

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)