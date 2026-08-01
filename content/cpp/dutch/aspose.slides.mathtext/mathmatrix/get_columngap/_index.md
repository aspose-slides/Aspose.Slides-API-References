---
title: get_ColumnGap()
second_title: Aspose.Slides voor C++ API-referentie
description: "De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt) Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), dan wordt de eenheid geïnterpreteerd als aantal 0.5 em stappen. In andere gevallen genegeerd. Standaard: 0"
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() methode


De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt) Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), dan wordt de eenheid geïnterpreteerd als het aantal 0.5 em stappen. In andere gevallen genegeerd. Standaard: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Zie ook

* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)