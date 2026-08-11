---
title: set_Rewind()
second_title: مرجع API Aspose.Slides للغة C++
description: تحدد هذه السمة ما إذا كان التأثير سيُعيد إلى البداية عند الانتهاء من التشغيل. اكتب bool.
type: docs
weight: 326
url: /ar/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) طريقة


هذه السمة تحدد ما إذا كان التأثير سيعود إلى الخلف عند الانتهاء من التشغيل. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

* الفئة [ITiming](../)
* مساحة الأسماء [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)