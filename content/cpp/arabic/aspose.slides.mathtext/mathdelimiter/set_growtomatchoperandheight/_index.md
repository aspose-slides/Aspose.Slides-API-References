---
title: set_GrowToMatchOperandHeight()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عند true، يزيد الفواصل عموديًا لتطابق ارتفاع العامل الخاص بها. القيمة الافتراضية هي true
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) طريقة

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عند true، يزيد الفواصل عمودياً لتطابق ارتفاع العامل الخاص بها. القيمة الافتراضية هي true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## ملاحظات


مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## انظر أيضًا

* الفئة [MathDelimiter](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)