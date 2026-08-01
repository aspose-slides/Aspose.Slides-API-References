---
title: set_RowSpacing()
second_title: Aspose.Slides voor C++ API Referentie
description: "Afstand tussen rijen van een array Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Exactly in welk geval de meeteenheid punten is of Multiple in welk geval de meeteenheid halve regels. Standaard: 0"
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) methode


Afstand tussen rijen van een array Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Exactly in welk geval de meeteenheid punten is of Multiple in welk geval de meeteenheid halve regels. Standaard: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
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