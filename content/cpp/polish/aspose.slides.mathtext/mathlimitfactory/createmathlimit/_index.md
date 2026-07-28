---
title: CreateMathLimit()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy IMathLimit
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metoda


Tworzy [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument bazowy do zastosowania limitu |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element limitu |
| upperLimit | **bool** | Ustawia położenie limitu na górze |

### Wartość zwracana

nowy limit matematyczny

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Tworzy [IMathLimit](../../imathlimit/) z limitem na dole

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument bazowy do zastosowania limitu |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element limitu |

### Wartość zwracana

nowy limit matematyczny

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathLimit](../../imathlimit/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathLimitFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)