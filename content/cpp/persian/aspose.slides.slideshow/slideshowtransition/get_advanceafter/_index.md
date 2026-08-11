---
title: get_AdvanceAfter()
second_title: Aspose.Slides برای C++ مرجع API
description: این ویژگی مشخص می‌کند که آیا اسلایدشو پس از زمان معینی به اسلاید بعدی می‌پردازد. خواندن bool.
type: docs
weight: 105
url: /fa/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() متد


این ویژگی مشخص می‌کند که آیا اسلایدشو پس از مدت زمان معینی به اسلاید بعدی می‌پردازد. خواندنی **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// دریافت اولین انتقال اسلاید
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// بررسی کنید آیا پرچم Advance Slide After فعال است
if (slideTransition->get_AdvanceAfter())
{
    // دریافت مقدار زمان Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## موارد مرتبط

* کلاس [SlideShowTransition](../)
* فضای‌نام [Aspose::Slides::SlideShow](../../)
* کتابخانه [Aspose.Slides](../../../)