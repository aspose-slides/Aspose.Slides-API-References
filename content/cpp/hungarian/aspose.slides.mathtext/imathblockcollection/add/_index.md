---
title: Add()
second_title: Aspose.Slides C++ API hivatkozás
description: Hozzáad egy IMathBlock objektumot a gyűjtemény végéhez.
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) metódus


A [IMathBlock](../../imathblock/)-t hozzáadja a gyűjtemény végére.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Egy matematikai blokk, amely a gyűjtemény végére lesz hozzáadva |
## Megjegyzések



Példa: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathBlockCollection](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)