---
title: get_DelimiterShape()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يحدد شكل الفواصل في كائن الفاصل. عندما تكون القيمة MathDelimiterShape::Centered، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي وتُصمم لتناسب كامل ارتفاع محتوياتها. عندما تكون القيمة MathDelimiterShape::Match، يتم تعديل ارتفاعها وشكلها لتطابق محتوياتها بدقة."
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## طريقة IMathDelimiter::get_DelimiterShape() method

يحدد شكل الفواصل في كائن الفاصل. عندما يكون [MathDelimiterShape::Centered](../../mathdelimitershape/)، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي وتُصمم لتناسب كامل ارتفاع محتوياتها. عندما يكون [MathDelimiterShape::Match](../../mathdelimitershape/)، يتم تعديل ارتفاعها وشكلها لتطابق محتوياتها بدقة.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## انظر أيضًا

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* فئة [IMathDelimiter](../)
* فضاء الأسماء [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)