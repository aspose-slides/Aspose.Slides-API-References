---
title: CreateMathLimit()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy IMathLimit
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metoda


Tworzy [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument bazowy, do którego zastosować limit |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element limitu |
| upperLimit | **bool** | Ustawia położenie limitu na górze |

### Wartość zwracana

nowy limit matematyczny

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Tworzy [IMathLimit](../../imathlimit/) z limitem na dole

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument bazowy, do którego zastosować limit |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element limitu |

### Wartość zwracana

nowy limit matematyczny

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathLimit](../../imathlimit/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathLimitFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)