---
title: Insert()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vkládá IMathBlock do kolekce na zadaném indexu.
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) metoda

Vloží [IMathBlock](../../imathblock/) do kolekce na určeném indexu.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na který by měla být položka vložena. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | [IMathBlock](../../imathblock/) k vložení. |

## Poznámky

Příklad: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)