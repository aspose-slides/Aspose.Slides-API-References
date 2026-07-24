---
title: set_Sound()
second_title: Aspose.Slides for C++ API Referansı
description: Efekt için gömülü ses tanımlandı. IAudio yazın.
type: docs
weight: 183
url: /tr/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) metodu


Efekt için gömülü ses tanımlandı. [IAudio](../../../aspose.slides/iaudio/) yazın.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Slayt için efekt sırasını alır
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Efekt sesini bayt dizisi olarak çıkarır
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudio](../../../aspose.slides/iaudio/)
* Sınıf [IEffect](../)
* İsim Uzayı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)