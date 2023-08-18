---
title: ToMathArray()
second_title: Aspose.Slides for C++ API Reference
description: Puts in a vertical array
type: docs
weight: 170
url: /aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() method


Puts in a vertical array

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
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
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)