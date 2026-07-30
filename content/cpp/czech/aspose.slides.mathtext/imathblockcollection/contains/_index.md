---
title: Contains()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, zda kolekce obsahuje konkrétní hodnotu.
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) metoda


Určuje, zda kolekce obsahuje konkrétní hodnotu.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objekt, který má být v kolekci vyhledán. |

### Návratová hodnota

true, pokud je *item* nalezen v kolekci; jinak false.
## Poznámky



Příklad: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)