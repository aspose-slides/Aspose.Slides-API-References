---
title: get_Limit()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان حد
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() متد


آرگومان حد

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## توضیحات


مثال: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathLimit](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)