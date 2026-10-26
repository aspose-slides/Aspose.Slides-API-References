---
title: Clear()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert alle elementen uit de collectie.
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() methode


Verwijdert alle elementen uit de collectie.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Zie ook

* Klasse [IMathBlockCollection](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)