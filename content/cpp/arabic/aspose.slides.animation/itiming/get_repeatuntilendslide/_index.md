---
title: get_RepeatUntilEndSlide()
second_title: مرجع API Aspose.Slides للغة C++
description: هذه السمة تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. اقرأ bool.
type: docs
weight: 131
url: /ar/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() طريقة

هذه السمة تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// يجلب تسلسل التأثيرات للشريحة الأولى
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// يجلب التأثير الأول للتسلسل الرئيسي.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// يغيّر توقيت/تكرار التأثير إلى "حتى نهاية الشريحة"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## انظر أيضًا

* الفئة [ITiming](../)
* النطاق [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)