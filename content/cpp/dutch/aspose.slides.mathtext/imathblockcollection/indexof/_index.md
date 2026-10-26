---
title: IndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt de index van een specifiek IMathBlock in de collectie.
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) method


Bepaalt de index van een specifiek [IMathBlock](../../imathblock/) in de collectie.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Het item om te zoeken in de collectie. |

### Retourwaarde

De index van *item* als deze in de collectie wordt gevonden; anders -1.
## Opmerkingen



Voorbeeld: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)