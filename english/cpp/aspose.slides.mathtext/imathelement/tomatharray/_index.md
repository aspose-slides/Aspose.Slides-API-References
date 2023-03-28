---
title: ToMathArray()
second_title: Aspose.Slides for C++ API Reference
description: Puts in a vertical array
type: docs
weight: 183
url: /cpp/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() method


Puts in a vertical array

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### Return Value

New instance of type [IMathArray](../../imatharray/)
## Remarks



Example: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathArray](../../imatharray/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
