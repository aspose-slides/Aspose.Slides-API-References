---
title: get_RowGap()
second_title: Aspose.Slides voor C++ API-referentie
description: "De waarde van de verticale afstand tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (\"Exactly\"), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Als de RowGapRule is ingesteld op 4 (\"Multiple\"), dan wordt de eenheid geïnterpreteerd als halve regels. Standaard: 0"
type: docs
weight: 183
url: /nl/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() methode

De waarde van de verticale afstand tussen rijen van een matrix; als de RowGapRule is ingesteld op 3 ("Exactly"), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) als de RowGapRule is ingesteld op 4 ("Multiple"), dan wordt de eenheid geïnterpreteerd als halve regels. Standaard: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Opmerkingen

Voorbeeld:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Zie ook

* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)