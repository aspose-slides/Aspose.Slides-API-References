---
title: CreateMathNaryOperator()
second_title: Aspose.Slides pro C++ - reference API
description: Vytváří IMathNaryOperator
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathnaryoperatorfactory/createmathnaryoperator/
---
## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Vytváří [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char16_t | Znak operátoru |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní argument pro aplikaci operátoru |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolní mez |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Horní mez |

### Návratová hodnota

nový [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Vytváří [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char16_t | Znak operátoru |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní argument pro aplikaci operátoru |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolní mez |

### Návratová hodnota

nový [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) method

Vytváří [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char16_t | Znak operátoru |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní argument pro aplikaci operátoru |

### Návratová hodnota

nový [IMathNaryOperator](../../imathnaryoperator/)

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathNaryOperator](../../imathnaryoperator/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathNaryOperatorFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)