---
title: CreateMathNaryOperator()
second_title: Aspose.Slides pro C++ API Reference
description: Vytváří IMathNaryOperator
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathnaryoperatorfactory/createmathnaryoperator/
---
## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Vytvoří [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit |

### Návratová hodnota

nový [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Vytvoří [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |

### Návratová hodnota

nový [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) metoda

Vytvoří [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |

### Návratová hodnota

nový [IMathNaryOperator](../../imathnaryoperator/)

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathNaryOperator](../../imathnaryoperator/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathNaryOperatorFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)