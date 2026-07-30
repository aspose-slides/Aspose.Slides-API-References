---
title: Radical()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje matematický kořen daného stupně ze zadaného argumentu.
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) metoda

Určuje matematický kořen daného stupně ze zadaného argumentu.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument of Radical |

### Návratová hodnota

Nová instance typu [IMathRadical](../../imathradical/)

## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) metoda

Určuje matematický kořen daného stupně ze zadaného argumentu.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
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
* Class [IMathRadical](../../imathradical/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)