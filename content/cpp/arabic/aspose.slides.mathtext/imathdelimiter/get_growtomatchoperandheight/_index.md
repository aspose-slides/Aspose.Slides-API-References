---
title: get_GrowToMatchOperandHeight()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما تكون true ينمو الفواصل عمودياً لتطابق ارتفاع معاملها. القيمة الافتراضية هي true
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() طريقة


يحدد نمو BeginningCharacter، SeparatorCharacter، EndingCharacter عندما تكون true، ينمو الفواصل عمودياً لتطابق ارتفاع معاملها. القيمة الافتراضية هي true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## ملاحظات


مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## انظر أيضًا

* الفئة [IMathDelimiter](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)