---
title: RemoveAt()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraní položku na zadaném indexu kolekce.
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) metoda


Odstraní položku na zadaném indexu kolekce.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově založený index položky, kterou chcete odstranit. |
## Poznámky



Příklad: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Viz také

* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)