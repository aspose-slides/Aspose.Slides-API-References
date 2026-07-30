---
title: Join()
second_title: Aspose.Slides pro C++ API referenci
description: Spojí matematický prvek a vytvoří matematický blok
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) metoda


Spojí matematický prvek a vytvoří matematický blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Prvek, který má být spojen |

### Návratová hodnota

Nový [IMathBlock](../../imathblock/) obsahující tuto instanci a zadaný argument
## Poznámky



Příklad: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) metoda


Spojí matematický text a vytvoří matematický blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Matematický text, který má být spojen |

### Návratová hodnota

Nový [IMathBlock](../../imathblock/) obsahující tuto instanci a zadaný argument
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)