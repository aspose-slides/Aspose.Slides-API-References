---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما تكون true، تنمو الفواصل عموديًا لتطابق ارتفاع معاملها. القيمة الافتراضية هي true
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() طريقة

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما تكون true، تنمو الفواصل عمودياً لتطابق ارتفاع المعامل الخاص بها. القيمة الافتراضية هي true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## ملاحظات


مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## انظر أيضا

* فئة [MathDelimiter](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)