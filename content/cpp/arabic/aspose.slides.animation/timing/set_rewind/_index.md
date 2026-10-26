---
title: set_Rewind()
second_title: مرجع API Aspose.Slides للـ C++
description: هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند انتهاء تشغيله. اكتب bool.
type: docs
weight: 248
url: /ar/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) طريقة

هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند الانتهاء من تشغيله. اكتب **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## انظر أيضًا

* الفئة [Timing](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)