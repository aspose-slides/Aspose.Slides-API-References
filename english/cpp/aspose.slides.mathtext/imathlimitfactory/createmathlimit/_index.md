---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API Reference
description: Creates IMathLimit
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, **bool**) method


Creates [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
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
* Class [IMathLimitFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathLimitFactory::CreateMathLimit([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) method


Creates [IMathLimit](../../imathlimit/) with limit at the bottom

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
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
* Class [IMathLimitFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
