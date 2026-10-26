---
title: set_Sound()
second_title: Aspose.Slides لـ C++ مرجع API
description: تم تعريف صوت مدمج للتأثير. اكتب IAudio.
type: docs
weight: 183
url: /ar/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) طريقة


تم تعريف صوت مدمج للتأثير. اكتب [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// يجلب تسلسل المؤثرات للشرريحة
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // يستخرج صوت المؤثر في مصفوفة بايت
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAudio](../../../aspose.slides/iaudio/)
* فئة [IEffect](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)