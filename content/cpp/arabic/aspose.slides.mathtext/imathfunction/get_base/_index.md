---
title: get_Base()
second_title: Aspose.Slides لـ C++ مرجع API
description: وسيط الدالة
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() طريقة

وسيط الدالة

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## ملاحظات

مثال:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathFunction](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)