---
title: idx_set()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací položku na zadaném indexu. Pouze pro čtení IMathBlock.
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) metoda

Vrací položku na zadaném indexu. Pouze pro čtení [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index položky, kterou chcete získat |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Blok matematického textu. |
## Poznámky



Příklad: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)