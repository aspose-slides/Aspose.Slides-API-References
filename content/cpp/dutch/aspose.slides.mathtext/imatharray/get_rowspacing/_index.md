---
title: get_RowSpacing()
second_title: Aspose.Slides voor C++ API-referentie
description: "Afstand tussen rijen van een array. Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3, exact in dat geval is de meeteenheid punten of Multiple, in dat geval is de meeteenheid halve regels. Standaard: 0"
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() methode


Afstand tussen rijen van een array Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Exact wanneer de meeteenheid punten is of Multiple wanneer de meeteenheid halve regels is. Standaard: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Zie ook

* Klasse [IMathArray](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)