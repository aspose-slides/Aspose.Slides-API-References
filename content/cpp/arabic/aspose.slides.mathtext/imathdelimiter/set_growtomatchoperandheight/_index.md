---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحدد نمو BeginningCharacter، SeparatorCharacter، EndingCharacter. عند true، تنمو الفواصل عمودياً لتطابق ارتفاع معاملها. القيمة الافتراضية هي true
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) طريقة

يحدد نمو BeginningCharacter، SeparatorCharacter، EndingCharacter. عندما يكون true، يتوسع الفواصل عمودياً ليتطابق مع ارتفاع المعامل. القيمة الافتراضية هي true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## ملاحظات

مثال: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## انظر أيضًا

* فئة [IMathDelimiter](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)