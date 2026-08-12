---
title: set_Sound()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดเสียงที่ฝังไว้สำหรับเอฟเฟกต์ เขียน IAudio.
type: docs
weight: 183
url: /th/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) เมธอด

กำหนดเสียงที่ฝังไว้สำหรับเอฟเฟกต์ เขียน [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## หมายเหตุ

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// ดึงลำดับเอฟเฟกต์สำหรับสไลด์
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // แยกเสียงของเอฟเฟกต์เป็นอาร์เรย์ของไบต์
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../../aspose.slides/iaudio/)
* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)