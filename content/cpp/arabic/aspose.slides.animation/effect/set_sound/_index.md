---
title: set_Sound()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تم تعريف الصوت المدمج للتأثير. اكتب IAudio.
type: docs
weight: 183
url: /ar/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) method


تعريف الصوت المدمج للتأثير. اكتب [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// يحصل على تسلسل التأثيرات للشفريحة
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // يستخرج صوت التأثير في مصفوفة بايت
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IAudio](../../../aspose.slides/iaudio/)
* الفئة [Effect](../)
* نطاق الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)