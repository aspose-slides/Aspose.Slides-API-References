---
title: CreateMathNaryOperator()
second_title: Aspose.Slides for C++ API Reference
description: Creates IMathNaryOperator
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathnaryoperatorfactory/createmathnaryoperator/
---
## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit |

### Return Value

new [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |

### Return Value

new [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) method


Creates [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |

### Return Value

new [IMathNaryOperator](../../imathnaryoperator/)

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [IMathNaryOperatorFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)