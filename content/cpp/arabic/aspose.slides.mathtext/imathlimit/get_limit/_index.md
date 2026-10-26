---
title: get_Limit()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: معامل الحد
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() طريقة


معامل الحد

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## ملاحظات


مثال: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathLimit](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)