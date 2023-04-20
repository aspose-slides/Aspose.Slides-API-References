---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API Reference
description: Creates a math accent applying to a specified math element with the default accent character value
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) method


Creates a math accent applying to a specified math element with the default accent character value

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply accent |

### Return Value

new math accent

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) method


Creates a math accent applying to a specified math element

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply accent |
| accentCharacter | char16_t | accent character |

### Return Value

new math accent

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../../imathelement/)
* Class [IMathAccentFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)