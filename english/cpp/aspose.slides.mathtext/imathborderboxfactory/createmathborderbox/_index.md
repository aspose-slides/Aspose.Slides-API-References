---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API Reference
description: Create a math border box by applying to the element
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method


Create a math border box by applying to the element

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply border box |

### Return Value

new border box element

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method


Create a math border box by applying to the element

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply border box |
| hideTop | **bool** | Hide Top Edge |
| hideBottom | **bool** | Hide Bottom Edge |
| hideLeft | **bool** | Hide Left Edge |
| hideRight | **bool** | Hide Right Edge |
| strikethroughHorizontal | **bool** | Border Box Strikethrough Horizontal |
| strikethroughVertical | **bool** | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | **bool** | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | **bool** | Border Box Strikethrough Top-Left to Bottom-Right |

### Return Value

new border box element

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)