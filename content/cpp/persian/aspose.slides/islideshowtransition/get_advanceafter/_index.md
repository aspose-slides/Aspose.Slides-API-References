---
title: get_AdvanceAfter()
second_title: مرجع API Aspose.Slides برای C++
description: این ویژگی مشخص می‌کند که آیا اسلایدشو پس از مدت زمانی معین به اسلاید بعدی منتقل شود یا خیر. خواندن bool.
type: docs
weight: 105
url: /fa/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISSlideShowTransition::get_AdvanceAfter() متد

این ویژگی مشخص می‌کند که آیا اسلایدشو پس از مدت زمانی به اسلاید بعدی منتقل شود یا خیر. خواندن **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// دریافت اولین انتقال اسلاید
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// بررسی فعال بودن پرچم Advance Slide After
if (slideTransition->get_AdvanceAfter())
{
    // دریافت مقدار زمان Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## موارد مرتبط

* کلاس [ISlideShowTransition](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)