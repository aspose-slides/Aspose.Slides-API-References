---
title: set_RowSpacing()
second_title: Aspose.Slides voor C++ API-referentie
description: "Afstand tussen rijen van een array Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Exact in dat geval is de meeteenheid punten of Multiple, in dat geval is de meeteenheid halfregels. Standaard: 0"
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) methode


Afstand tussen rijen van een array Het wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Exact in dat geval is de meeteenheid punten of Multiple, in dat geval is de meeteenheid half-lines. Standaard: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
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