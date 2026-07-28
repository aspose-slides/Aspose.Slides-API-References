---
title: CreateMathNaryOperator()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy IMathNaryOperator
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathnaryoperatorfactory/createmathnaryoperator/
---
## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Tworzy [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char16_t | Znak operatora |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument bazowy do zastosowania operatora |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Granica dolna |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Granica górna |

### Wartość zwracana

new [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Tworzy [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char16_t | Znak operatora |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument bazowy do zastosowania operatora |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Granica dolna |

### Wartość zwracana

new [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) metoda


Tworzy [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char16_t | Znak operatora |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument bazowy do zastosowania operatora |

### Wartość zwracana

new [IMathNaryOperator](../../imathnaryoperator/)

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathNaryOperator](../../imathnaryoperator/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathNaryOperatorFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)