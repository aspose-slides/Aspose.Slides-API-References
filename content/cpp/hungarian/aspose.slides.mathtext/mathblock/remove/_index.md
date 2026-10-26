---
title: Remove()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja a megadott objektum első előfordulását a gyűjteményből.
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) metódus


Eltávolítja a konkrét objektum első előfordulását a gyűjteményből.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az eltávolítandó objektum a gyűjteményben. |

### Visszatérési érték

true ha az *item* sikeresen eltávolításra került a gyűjteményből; egyébként false. Ez a metódus szintén false értékkel tér vissza, ha az *item* nem található az eredeti gyűjteményben.
## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)