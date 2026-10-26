---
title: get_Rewind()
second_title: Aspose.Slides لمرجع API C++
description: هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند انتهاء التشغيل. اقرأ bool.
type: docs
weight: 313
url: /ar/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() طريقة

هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند انتهاء التشغيل. اقرأ **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على تسلسل التأثيرات للشريحة الأولى
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// احصل على أول تأثير في التسلسل الرئيسي.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// فعّل توقيت/إعادة تشغيل التأثير.
effect->get_Timing()->set_Rewind(true);
```

## انظر أيضًا

* فئة [ITiming](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)