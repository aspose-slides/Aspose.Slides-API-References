---
title: Contains()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, zda kolekce obsahuje konkrétní hodnotu.
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/mathblock/contains/
---
## MathBlock::Contains(System::SharedPtr\<IMathElement\>) metoda

Určuje, zda kolekce obsahuje konkrétní hodnotu.

```cpp
bool Aspose::Slides::MathText::MathBlock::Contains(System::SharedPtr<IMathElement> item) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Objekt, který se má vyhledat v kolekci. |

### Návratová hodnota

true pokud je *item*  nalezen v kolekci; jinak false.
## Poznámky



Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = mathBlock->Contains(plusElement);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)