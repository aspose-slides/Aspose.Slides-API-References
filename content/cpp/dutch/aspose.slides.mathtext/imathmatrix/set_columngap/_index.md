---
title: set_ColumnGap()
second_title: Aspose.Slides voor C++ API-referentie
description: "De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt) Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), dan wordt de eenheid geïnterpreteerd als aantal van 0,5 em-incrementen. In andere gevallen genegeerd. Standaard: 0"
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) methode


De waarde van de horizontale afstand tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt) Als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), dan wordt de eenheid geïnterpreteerd als aantal van 0,5 em-incrementen. In andere gevallen wordt genegeerd. Standaard: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Zie ook

* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)