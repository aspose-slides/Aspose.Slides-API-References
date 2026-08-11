---
title: set_AdvanceAfter()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد مدة زمنية معينة. اكتب bool.
type: docs
weight: 118
url: /ar/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) طريقة

هذه الخاصية تحدد ما إذا كان العرض التقديمي سينتقل إلى الشريحة التالية بعد فترة زمنية معينة. اكتب **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// الحصول على أول انتقال شريحة
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// تحقق مما إذا تم تفعيل علم الانتقال بعد
if (slideTransition->get_AdvanceAfter())
{
    // احصل على قيمة زمن الانتقال بعد
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## انظر أيضًا

* الفئة [SlideShowTransition](../)
* النطاق [Aspose::Slides::SlideShow](../../)
* المكتبة [Aspose.Slides](../../../)