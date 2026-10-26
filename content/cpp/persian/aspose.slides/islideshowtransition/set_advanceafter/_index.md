---
title: set_AdvanceAfter()
second_title: Aspose.Slides برای C++ API Reference
description: این ویژگی مشخص می‌کند که آیا نمایش اسلاید پس از زمان معینی به اسلاید بعدی منتقل می‌شود. مقدار bool را بنویسید.
type: docs
weight: 118
url: /fa/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) متد


این ویژگی مشخص می‌کند که آیا نمایش اسلاید پس از زمان معینی به اسلاید بعدی منتقل می‌شود. مقدار **bool** را بنویسید.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// دریافت اولین انتقال اسلاید
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// بررسی اینکه آیا پرچم Advance Slide After فعال است
if (slideTransition->get_AdvanceAfter())
{
    // دریافت مقدار زمان Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## مراجع

* کلاس [ISlideShowTransition](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)