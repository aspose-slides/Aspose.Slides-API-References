---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API Reference
description: Creates subscript and superscript on the left
type: docs
weight: 118
url: /cpp/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates subscript and superscript on the left

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lower index on the left) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (upper index on the left) |

### Return Value

New math element of type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) method


Creates subscript and superscript on the left

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the left) |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the left) |

### Return Value

New math element of type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)