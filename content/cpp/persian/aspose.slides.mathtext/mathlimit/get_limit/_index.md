---
title: get_Limit()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان محدودیت
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() متد

آرگومان محدودیت

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## توضیحات

مثال: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathLimit](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)