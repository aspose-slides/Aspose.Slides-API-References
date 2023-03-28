---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API Reference
description: Creates superscript
type: docs
weight: 79
url: /cpp/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) method


Creates superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (upper index on the right) |

### Return Value

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathElementBase::SetSuperscript([System::String](../../../system/string/)) method


Creates superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
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
* Class [String](../../../system/string/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
