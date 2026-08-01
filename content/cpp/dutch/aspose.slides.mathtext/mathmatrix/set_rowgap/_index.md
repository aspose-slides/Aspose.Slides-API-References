---
title: set_RowGap()
second_title: Aspose.Slides voor C++ API-referentie
description: "De waarde van de verticale ruimte tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 (\"Exactly\"), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Als de RowGapRule is ingesteld op 4 (\"Multiple\"), dan wordt de eenheid geïnterpreteerd als halve regels. Standaard: 0"
type: docs
weight: 196
url: /nl/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) methode

De waarde van de verticale afstand tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 ("Exactly"), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) Als de RowGapRule is ingesteld op 4 ("Multiple"), dan wordt de eenheid geïnterpreteerd als halve regels. Standaard: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
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