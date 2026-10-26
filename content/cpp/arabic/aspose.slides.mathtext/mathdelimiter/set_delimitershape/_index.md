---
title: set_DelimiterShape()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد شكل الفواصل في كائن الفاصل. عندما تكون MathDelimiterShape::Centered، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي وتُصنع لتتناسب مع الارتفاع الكامل لمحتواها. عندما تكون MathDelimiterShape::Match، يتم تعديل ارتفاعها وشكلها لتطابق محتواها بدقة."
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) طريقة

يحدد شكل الفواصل في كائن الفاصل. عندما يكون [MathDelimiterShape::Centered](../../mathdelimitershape/)، يتم توسيط الفواصل حول محور الرياضيات للنص الرياضي وتُصنع لتناسب كامل ارتفاع محتواها. عندما يكون [MathDelimiterShape::Match](../../mathdelimitershape/)، يتم تعديل ارتفاعها وشكلها لتطابق محتواها بدقة.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## ملاحظات

مثال:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## انظر أيضًا

* تعداد [MathDelimiterShape](../../mathdelimitershape/)
* فئة [MathDelimiter](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)