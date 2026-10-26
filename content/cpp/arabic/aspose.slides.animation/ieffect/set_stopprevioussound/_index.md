---
title: set_StopPreviousSound()
second_title: مرجع API Aspose.Slides للغة C++
description: تحدد هذه السمة ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اكتب bool.
type: docs
weight: 209
url: /ar/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) طريقة


تُحدد هذه السمة ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// الحصول على التأثير الأول للشريحة الأولى.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// الحصول على التأثير الأول للشريحة الثانية.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // تغيير تحسينات/الصوت للتأثير الثاني إلى "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## انظر أيضًا

* فئة [IEffect](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)