---
title: Remove()
second_title: Aspose.Slides for C++ API-referencia
description: Eltávolítja a gyűjteményből egy adott objektum első előfordulását.
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) metódus


Eltávolítja egy adott objektum első előfordulását a gyűjteményből.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A gyűjteményből eltávolítandó objektum. |

### Visszatérési érték

true, ha a *item* sikeresen eltávolításra került a gyűjteményből; egyébként false. Ez a metódus is false értéket ad vissza, ha a *item* nem található az eredeti gyűjteményben.

## Megjegyzések



Példa: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathElementCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)