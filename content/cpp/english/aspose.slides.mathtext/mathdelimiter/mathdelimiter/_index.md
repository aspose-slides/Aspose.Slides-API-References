---
title: MathDelimiter()
second_title: Aspose.Slides for C++ API Reference
description: Initializes MathDelimiter with the specified element as single base argument
type: docs
weight: 144
url: /aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) constructor


Initializes [MathDelimiter](../) with the specified element as single base argument

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The base element to which the delimiter is applied. Can be null. |

### Exceptions

| Exception | Description |
| --- | --- |
| T:System::InvalidOperationException | Throws then *element*  is a container for another elements, such as [MathBlock](../../mathblock/). In this case, you need to call a different constructor with IEnumerable argument. |

## Remarks



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)