---
title: ToBox()
second_title: Aspose.Slides for C++ API Reference
description: Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.
type: docs
weight: 274
url: /aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() method


Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
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
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)