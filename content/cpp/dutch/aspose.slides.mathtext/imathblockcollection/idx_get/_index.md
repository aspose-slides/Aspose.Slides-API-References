---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het item op de opgegeven index op. Alleen-lezen IMathBlock.
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) methode


Haalt het item op de opgegeven index op. Alleen-lezen [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het op te halen item |

### Retourwaarde

Het blok van een wiskundige tekst.
## Opmerkingen



Voorbeeld: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)