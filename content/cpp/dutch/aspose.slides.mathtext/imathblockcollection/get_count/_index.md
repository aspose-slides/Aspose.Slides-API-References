---
title: get_Count()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int32_t.
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() methode


Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Zie ook

* Klasse [IMathBlockCollection](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)