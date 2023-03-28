---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides for C++ API Reference
description: Creates subscript and superscript on the right
type: docs
weight: 105
url: /cpp/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\>) method


Creates subscript and superscript on the right

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lower index on the right) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (upper index on the right) |

### Return Value

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [IMathElement](../)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathElement::SetSubSuperscriptOnTheRight([System::String](../../../system/string/), [System::String](../../../system/string/)) method


Creates subscript and superscript on the right

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the right) |

### Return Value

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [String](../../../system/string/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
