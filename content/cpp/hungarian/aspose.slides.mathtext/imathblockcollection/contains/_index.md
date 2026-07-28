---
title: Contains()
second_title: Aspose.Slides for C++ API referencia
description: Meghatározza, hogy a gyűjtemény tartalmaz-e egy adott értéket.
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) metódus


Meghatározza, hogy a gyűjtemény tartalmaz-e egy adott értéket.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Az objektum, amelyet a gyűjteményben keresni kell. |

### Visszatérési érték

igaz, ha *item*  megtalálható a gyűjteményben; egyébként hamis.
## Megjegyzés



Példa: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathBlockCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)