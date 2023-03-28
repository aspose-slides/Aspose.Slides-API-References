---
title: Join()
second_title: Aspose.Slides for C++ API Reference
description: Joins a mathematical element and forms a mathematical block
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\>) method


Joins a mathematical element and forms a mathematical block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | The element to be joined |

### Return Value

A new [IMathBlock](../../imathblock/) containing this instance and specified argument
## Remarks



Example: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathElement](../)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathElement::Join([System::String](../../../system/string/)) method


Joins a mathematical text and forms a mathematical block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Mathematical text to be joined |

### Return Value

A new [IMathBlock](../../imathblock/) containing this instance and specified argument
## Remarks



Example: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [String](../../../system/string/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
