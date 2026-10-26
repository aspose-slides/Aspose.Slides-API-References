---
title: Remove()
second_title: Aspose.Slides a C++ API referenciája
description: Eltávolítja egy adott objektum első előfordulását a gyűjteményből/>
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) metódus


Eltávolítja a konkrét objektum első előfordulását a gyűjteményből/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Az objektum, amelyet el kell távolítani a gyűjteményből. |

### Visszatérési érték

true, ha a *item* sikeresen eltávolításra került a gyűjteményből; egyébként false. Ez a metódus szintén false értéket ad, ha a *item* nem található az eredeti gyűjteményben/>.

## Megjegyzés



Példa: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathBlockCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)