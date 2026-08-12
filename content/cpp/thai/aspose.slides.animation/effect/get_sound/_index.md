---
title: get_Sound()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดเสียงฝังตัวสำหรับเอฟเฟกต์ อ่าน IAudio.
type: docs
weight: 170
url: /th/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() เมธอด


กำหนดเสียงฝังตัวสำหรับเอฟเฟกต์ อ่าน [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// รับลำดับเอฟเฟกต์สำหรับสไลด์
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // ดึงเสียงเอฟเฟกต์เป็นอาเรย์ไบต์
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../../aspose.slides/iaudio/)
* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)