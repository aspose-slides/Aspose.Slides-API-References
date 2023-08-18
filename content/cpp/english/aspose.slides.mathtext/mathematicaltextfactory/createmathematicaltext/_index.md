---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API Reference
description: Create empty mathematical text element
type: docs
weight: 1
url: /aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() method


Create empty mathematical text element

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### Return Value

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) method


Create mathematical text element with the specified value

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | single symbol to use as text value |

### Return Value

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) method


Create empty mathematical text element with the specified value

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | text value |

### Return Value

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method


Create empty mathematical text element with the specified value and formatting properties

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | text value |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | text format settings |

### Return Value

new Mathematical Text

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [MathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)