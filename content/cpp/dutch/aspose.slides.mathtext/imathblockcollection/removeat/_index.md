---
title: RemoveAt()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert een item op de opgegeven index van de collectie.
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) methode

Verwijdert een item op de opgegeven index van de collectie.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het te verwijderen item. |
## Opmerkingen

Voorbeeld:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Zie ook

* Klasse [IMathBlockCollection](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)