---
title: get_Limit()
second_title: مرجع API Aspose.Slides للغة C++
description: معامل الحد
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() طريقة


معامل الحد

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## ملاحظات


مثال:

```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## انظر أيضا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathLimit](../)
* فضاء الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)