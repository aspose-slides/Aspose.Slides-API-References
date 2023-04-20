---
title: MathDelimiter()
second_title: Aspose.Slides for C++ API Reference
description: Initializes MathDelimiter with the specified element as single base argument
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
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