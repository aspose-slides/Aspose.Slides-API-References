---
title: set_DelimiterShape()
second_title: "Aspose.Slides للغة C++ – مرجع API"
description: "يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape::Centered، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي وتُضبط لتلائم كامل ارتفاع محتواها. عندما يكون MathDelimiterShape::Match، يتم تعديل ارتفاعها وشكلها لتطابق محتواها تمامًا."
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) طريقة

يحدد شكل الفواصل في كائن الفاصل. عندما يكون [MathDelimiterShape::Centered](../../mathdelimitershape/)، يتم تمركز الفواصل حول محور الرياضيات للنص الرياضي وتُجعل لتلائم كامل ارتفاع محتواها. عندما يكون [MathDelimiterShape::Match](../../mathdelimitershape/)، يتم تعديل ارتفاعها وشكلها ليتطابق تمامًا مع محتواها.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## ملاحظات


مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## انظر أيضا

* تعداد [MathDelimiterShape](../../mathdelimitershape/)
* فئة [IMathDelimiter](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)