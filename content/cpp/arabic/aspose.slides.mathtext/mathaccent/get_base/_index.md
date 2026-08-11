---
title: get_Base()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: الوسيط الذي تم تطبيق التنوين عليه
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() طريقة


الوسيط الذي تم تطبيق التنوين عليه

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## ملاحظات


مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathAccent](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)