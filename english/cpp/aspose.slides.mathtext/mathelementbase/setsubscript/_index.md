---
title: SetSubscript()
second_title: Aspose.Slides for C++ API Reference
description: Creates subscript
type: docs
weight: 66
url: /cpp/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) method


Creates subscript

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (lower index on the right) |

### Return Value

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) method


Creates subscript

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
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
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)