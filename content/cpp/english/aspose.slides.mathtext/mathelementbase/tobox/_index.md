---
title: ToBox()
second_title: Aspose.Slides for C++ API Reference
description: Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.
type: docs
weight: 261
url: /aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() method


Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### Return Value

Logical box with this element placed inside
## Remarks



Example: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBox](../../imathbox/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)