---
title: idx_set()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het item op de gespecificeerde index op. Alleen-lezen IMathBlock.
type: docs
weight: 105
url: /nl/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) method


Haalt het item op de gespecificeerde index. Alleen-lezen [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het item dat moet worden opgehaald |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Het blok van een wiskundige tekst. |
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
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)