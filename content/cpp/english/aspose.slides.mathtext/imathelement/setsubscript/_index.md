---
title: SetSubscript()
second_title: Aspose.Slides for C++ API Reference
description: Creates subscript
type: docs
weight: 79
url: /aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) method


Creates subscript

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lower index on the right) |

### Return Value

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) method


Creates subscript

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |

### Return Value

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathSubscriptElement](../../imathsubscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)