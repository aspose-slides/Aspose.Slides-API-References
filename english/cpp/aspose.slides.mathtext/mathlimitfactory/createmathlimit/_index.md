---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API Reference
description: Creates IMathLimit
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, **bool**) method


Creates [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply the limit |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit element |
| upperLimit | **bool** | Sets the placement of the limit on top |

### Return Value

new math limit

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../../imathelement/)
* Class [MathLimitFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathLimitFactory::CreateMathLimit([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) method


Creates [IMathLimit](../../imathlimit/) with limit at the bottom

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply the limit |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit element |

### Return Value

new math limit

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../../imathelement/)
* Class [MathLimitFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
