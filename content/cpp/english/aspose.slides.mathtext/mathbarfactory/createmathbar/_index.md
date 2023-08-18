---
title: CreateMathBar()
second_title: Aspose.Slides for C++ API Reference
description: Create a math bar by applying to the element
type: docs
weight: 1
url: /aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) method


Create a math bar by applying to the element

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply bar |

### Return Value

new math bar element

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) method


Create a math bar by applying to the element

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Math element to apply bar |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position of the bar |

### Return Value

new math bar element

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBar](../../imathbar/)
* Class [IMathElement](../../imathelement/)
* Class [MathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)