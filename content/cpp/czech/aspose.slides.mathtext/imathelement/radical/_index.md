---
title: Radical()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje matematický kořen zadaného řádu ze specifikovaného argumentu.
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) metoda


Určuje matematický kořen daného řádu ze zadaného argumentu.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument of Radical |

### Návratová hodnota

Nová instance typu [IMathRadical](../../imathradical/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) metoda


Určuje matematický kořen daného řádu ze zadaného argumentu.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### Návratová hodnota

Nová instance typu [IMathRadical](../../imathradical/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathRadical](../../imathradical/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)