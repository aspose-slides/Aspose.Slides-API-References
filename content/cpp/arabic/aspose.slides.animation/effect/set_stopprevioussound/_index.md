---
title: set_StopPreviousSound()
second_title: مرجع API Aspose.Slides لـ C++
description: تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اكتب bool.
type: docs
weight: 209
url: /ar/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) طريقة

هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اكتب **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
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
    // تغيير تحسينات/صوت التأثير الثاني إلى "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```
## انظر أيضًا

* الفئة [Effect](../)
* النطاق [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)