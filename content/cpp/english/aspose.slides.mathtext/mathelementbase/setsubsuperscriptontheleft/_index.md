---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API Reference
description: Creates subscript and superscript on the left
type: docs
weight: 105
url: /aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates subscript and superscript on the left

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (lower index on the left) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (upper index on the left) |

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

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) method


Creates subscript and superscript on the left

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
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
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)