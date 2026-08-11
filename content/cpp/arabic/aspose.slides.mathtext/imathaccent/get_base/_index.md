---
title: get_Base()
second_title: مرجع API Aspose.Slides للـ C++
description: الوسيط الذي تم تطبيق اللكنة عليه
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() طريقة

الوسيط الذي تم تطبيق اللكنة عليه

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
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
* فئة [IMathAccent](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)