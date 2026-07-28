---
title: idx_set()
second_title: Aspose.Slides for C++ API Referencia
description: Lekéri a megadott indexű elemet. Csak olvasható IMathBlock.
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) method


A megadott indexű elemet adja vissza. Csak olvasható [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A lekérdezendő elem nulláktól induló indexe |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | A matematikai szöveg blokkja. |
## Megjegyzés



Példa: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathBlockCollection](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)