---
title: Join()
second_title: Aspose.Slides for C++ API Reference
description: Joins a mathematical element with this mathematical block
type: docs
weight: 183
url: /cpp/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) method


Joins a mathematical element with this mathematical block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The element to be joined |

### Return Value

The current instance of [IMathBlock](../../imathblock/)
## Remarks



Example: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) method


Joins a mathematical text with this mathematical block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
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
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)