---
title: Radical()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) metoda


Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument pierwiastka |

### Wartość zwracana

Nowa instancja typu [IMathRadical](../../imathradical/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) metoda


Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
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
* Class [IMathRadical](../../imathradical/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)