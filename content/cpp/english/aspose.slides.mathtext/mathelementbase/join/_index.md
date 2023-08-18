---
title: Join()
second_title: Aspose.Slides for C++ API Reference
description: Joins a mathematical element and forms a mathematical block
type: docs
weight: 1
url: /aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) method


Joins a mathematical element and forms a mathematical block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The element to be joined |

### Return Value

A new [IMathBlock](../../imathblock/) containing this instance and specified argument
## Remarks



Example: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) method


Joins a mathematical text and forms a mathematical block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
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
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)