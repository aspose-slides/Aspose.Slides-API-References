---
title: get_RowSpacing()
second_title: Aspose.Slides voor C++ API Referentie
description: "Spatiëring tussen rijen van een array Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Precies in welk geval de meeteenheid punten is of Multiple in welk geval de meeteenheid halve-lijnen. Standaard: 0"
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() methode

Spatiëring tussen rijen van een array Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Precies in welk geval de meeteenheid punten is of Multiple in welk geval de meeteenheid halve-lijnen. Standaard: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Zie ook

* Klasse [MathArray](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)