---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API Reference
description: Creates superscript
type: docs
weight: 92
url: /aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) method


Creates superscript

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (upper index on the right) |

### Return Value

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) method


Creates superscript

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the right) |

### Return Value

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)