---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ مرجع API
description: تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة bool.
type: docs
weight: 196
url: /ar/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() طريقة


هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // غيّر تأثير الثاني Enhancements/Sound إلى "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## انظر أيضًا

* فئة [Effect](../)
* مساحة اسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)