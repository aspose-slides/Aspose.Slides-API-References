---
title: get_Base()
second_title: Aspose.Slides لـ C++ مرجع API
description: معامل الدالة
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() طريقة


معامل الدالة

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## ملاحظات


مثال: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathFunction](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)