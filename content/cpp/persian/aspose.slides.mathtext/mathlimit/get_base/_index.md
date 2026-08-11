---
title: get_Base()
second_title: Aspose.Slides برای C++ مرجع API
description: آرگومان پایه
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() متد


آرگومان پایه

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## توضیحات


مثال: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## ارجاع‌ها

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathLimit](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)