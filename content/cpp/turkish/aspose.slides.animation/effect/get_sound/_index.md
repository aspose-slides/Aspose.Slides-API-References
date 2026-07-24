---
title: get_Sound()
second_title: Aspose.Slides for C++ API Referansı
description: Efekt için tanımlanmış gömülü ses. IAudio'ı okuyun.
type: docs
weight: 170
url: /tr/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() yöntemi


Efekt için tanımlanmış gömülü ses. Okuyun [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

//    Slayt için efekt dizisini alır
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    //        Efekt sesini bayt dizisi olarak çıkarır
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudio](../../../aspose.slides/iaudio/)
* Sınıf [Effect](../)
* Ad Alanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)