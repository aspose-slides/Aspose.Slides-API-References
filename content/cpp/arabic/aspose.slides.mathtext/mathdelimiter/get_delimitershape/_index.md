---
title: get_DelimiterShape()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape::Centered، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي ولا تزال تُصمم لتتناسب مع الارتفاع الكامل لمحتوياتها. عندما يكون MathDelimiterShape::Match، يتم تعديل ارتفاعها وشكلها لتطابق محتوياتها بدقة."
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() طريقة

يحدد شكل الفواصل في كائن الفواصل. عندما يكون [MathDelimiterShape::Centered](../../mathdelimitershape/)، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي ولا تزال تُصنع لتناسب كامل ارتفاع محتوياتها. عندما يكون [MathDelimiterShape::Match](../../mathdelimitershape/)، يتم تعديل ارتفاعها وشكلها لتطابق محتوياتها تمامًا.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## انظر أيضاً

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* فئة [MathDelimiter](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)