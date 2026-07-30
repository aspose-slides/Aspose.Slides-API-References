---
title: IndexOf()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje index konkrétního IMathBlock ve sbírce.
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) metoda

Určuje index konkrétního [IMathBlock](../../imathblock/) ve sbírce.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Položka, kterou je třeba najít ve sbírce. |

### Návratová hodnota

Index *item* pokud je ve sbírce nalezen; jinak -1.

## Poznámky

Příklad: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)