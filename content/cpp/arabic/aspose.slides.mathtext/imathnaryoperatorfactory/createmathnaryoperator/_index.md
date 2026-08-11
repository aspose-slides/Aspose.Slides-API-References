---
title: CreateMathNaryOperator()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ IMathNaryOperator
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathnaryoperatorfactory/createmathnaryoperator/
---
## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة

ينشئ [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit |

### قيمة الإرجاع

جديد [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة

ينشئ [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |

### قيمة الإرجاع

جديد [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) طريقة


ينشئ [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |

### قيمة الإرجاع

جديد [IMathNaryOperator](../../imathnaryoperator/)

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [IMathNaryOperatorFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)