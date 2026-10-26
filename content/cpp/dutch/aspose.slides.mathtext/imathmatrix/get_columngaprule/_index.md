---
title: get_ColumnGapRule()
second_title: Aspose.Slides voor C++ API-referentie
description: "Het type horizontale afstand tussen kolommen van een matrix; horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)"
type: docs
weight: 105
url: /nl/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() methode


Het type horizontale afstand tussen kolommen van een matrix; horizontale afstandseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Zie ook

* Enum [MathSpacingRules](../../mathspacingrules/)
* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)