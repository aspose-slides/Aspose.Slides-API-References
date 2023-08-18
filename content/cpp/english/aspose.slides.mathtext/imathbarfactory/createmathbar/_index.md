---
title: CreateMathBar()
second_title: Aspose.Slides for C++ API Reference
description: Create a math bar by applying to the element
type: docs
weight: 1
url: /aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) method


Create a math bar by applying to the element

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply bar |

### Return Value

new math bar element

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) method


Create a math bar by applying to the element

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
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
* Class [IMathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)