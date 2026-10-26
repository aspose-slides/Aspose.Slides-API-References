---
title: Radical()
second_title: Aspose.Slides dla C++ Referencja API
description: Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) metoda

Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument pierwiastka |

### Wartość zwracana

Nowa instancja typu [IMathRadical](../../imathradical/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) metoda

Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument pierwiastka |

### Wartość zwracana

Nowa instancja typu [IMathRadical](../../imathradical/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathRadical](../../imathradical/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)