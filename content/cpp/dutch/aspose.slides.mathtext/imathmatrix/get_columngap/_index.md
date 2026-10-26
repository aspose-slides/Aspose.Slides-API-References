---
title: get_ColumnGap()
second_title: Aspose.Slides voor C++ API Referentie
description: "De waarde van de horizontale tussenruimte tussen kolommen van een matrix; als de ColumnGapRule is ingesteld op 3 (\"Exactly\"), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt) als de ColumnGapRule is ingesteld op 4 (\"Multiple\"), dan wordt de eenheid geïnterpreteerd als een aantal van 0.5 em-stappen. In andere gevallen genegeerd. Standaard: 0"
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() methode

De waarde van de horizontale tussenruimte tussen kolommen van een matrix; als de ColumnGapRule is ingesteld op 3 ("Exactly"), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt). Als de ColumnGapRule is ingesteld op 4 ("Multiple"), dan wordt de eenheid geïnterpreteerd als een aantal van 0,5 em-stappen. In andere gevallen wordt genegeerd. Standaard: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
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