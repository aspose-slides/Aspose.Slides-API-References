---
title: get_Sound()
second_title: Aspose.Slides for C++ API Referansı
description: Etkisi için tanımlı gömülü ses. Okuyun IAudio.
type: docs
weight: 170
url: /tr/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() metodu


Etkisi için tanımlı gömülü ses. [IAudio](../../../aspose.slides/iaudio/) öğesini okuyun.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Slayt için efekt dizisini alır
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Efekt sesini bayt dizisine çıkarır
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Başvurular

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudio](../../../aspose.slides/iaudio/)
* Sınıf [IEffect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)