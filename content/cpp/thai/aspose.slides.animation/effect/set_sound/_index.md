---
title: set_Sound()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดเสียงฝังสำหรับเอฟเฟกต์ เขียน IAudio.
type: docs
weight: 183
url: /th/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) เมธอด

กำหนดเสียงฝังสำหรับเอฟเฟกต์. เขียน [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// ดึงลำดับของเอฟเฟกต์สำหรับสไลด์
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // สกัดเสียงเอฟเฟกต์เป็นอาร์เรย์ของไบต์
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../../aspose.slides/iaudio/)
* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)