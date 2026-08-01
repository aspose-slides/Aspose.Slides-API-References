---
title: Contains()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de collectie een specifieke waarde bevat.
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) methode


Bepaalt of de collectie een specifieke waarde bevat.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Het object dat in de collectie moet worden gezocht. |

### Retourwaarde

true als *item* in de collectie wordt gevonden; anders false.
## Opmerkingen



Voorbeeld:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)