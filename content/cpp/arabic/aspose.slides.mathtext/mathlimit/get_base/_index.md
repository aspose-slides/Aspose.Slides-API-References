---
title: get_Base()
second_title: مرجع API Aspose.Slides للغة C++
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() طريقة

Base معامل

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## ملاحظات

مثال:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathLimit](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)