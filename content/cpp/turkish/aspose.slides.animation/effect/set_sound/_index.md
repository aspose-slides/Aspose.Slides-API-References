---
title: set_Sound()
second_title: Aspose.Slides için C++ API Referansı
description: Etki için gömülü sesi tanımlar. IAudio yazın.
type: docs
weight: 183
url: /tr/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) metodu

Etki için gömülü sesi tanımlar. [IAudio](../../../aspose.slides/iaudio/) yazın.

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
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

    // Etki sesini bayt dizisi olarak çıkarır
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudio](../../../aspose.slides/iaudio/)
* Sınıf [Effect](../)
* Ad alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)