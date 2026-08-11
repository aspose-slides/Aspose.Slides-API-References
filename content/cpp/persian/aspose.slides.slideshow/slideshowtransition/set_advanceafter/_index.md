---
title: set_AdvanceAfter()
second_title: Aspose.Slides برای C++ مرجع API
description: این ویژگی مشخص می‌کند که آیا اسلایدشو پس از یک زمان معین به اسلاید بعدی می‌پرد. نوشتن bool.
type: docs
weight: 118
url: /fa/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) متد


این ویژگی مشخص می‌کند که آیا اسلایدشو پس از یک زمان معین به اسلاید بعدی می‌پرد. نوشتن **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// دریافت اولین انتقال اسلاید
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// بررسی فعال بودن پرچم پیشروی اسلاید پس از زمان
if (slideTransition->get_AdvanceAfter())
{
    // دریافت مقدار زمان پیشروی اسلاید
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## مراجعه

* کلاس [SlideShowTransition](../)
* فضای‌نام [Aspose::Slides::SlideShow](../../)
* کتابخانه [Aspose.Slides](../../../)