---
title: get_StopPreviousSound()
second_title: مرجع API ل Aspose.Slides للـ C++
description: تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة bool.
type: docs
weight: 196
url: /ar/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() طريقة


تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// الحصول على التأثير الأول في الشريحة الأولى.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// الحصول على التأثير الأول في الشريحة الثانية.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // تغيير تحسينات/الصوت في التأثير الثاني إلى "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## انظر أيضاً

* الفئة [IEffect](../)
* النطاق [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)