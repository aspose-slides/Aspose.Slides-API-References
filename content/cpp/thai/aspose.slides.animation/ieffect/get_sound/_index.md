---
title: get_Sound()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดเสียงฝังไว้สำหรับเอฟเฟกต์. อ่าน IAudio.
type: docs
weight: 170
url: /th/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() วิธี


กำหนดเสียงฝังไว้สำหรับเอฟเฟกต์ อ่าน [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
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

    // สกัดเสียงเอฟเฟกต์เป็นอาร์เรย์ไบต์
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../../aspose.slides/iaudio/)
* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)