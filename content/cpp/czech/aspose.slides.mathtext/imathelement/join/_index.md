---
title: Join()
second_title: Aspose.Slides pro C++ - referenční API
description: Spojí matematický prvek a vytvoří matematický blok
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) metoda


Spojí matematický prvek a vytvoří matematický blok

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Prvek, který má být spojen |

### Návratová hodnota

Nový [IMathBlock](../../imathblock/) obsahující tuto instanci a zadaný argument
## Poznámky



Příklad: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) metoda


Spojí matematický text a vytvoří matematický blok

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
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
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)