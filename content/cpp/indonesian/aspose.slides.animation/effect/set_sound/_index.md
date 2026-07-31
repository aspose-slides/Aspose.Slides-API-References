---
title: set_Sound()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan suara tersemat untuk efek. Tulis IAudio.
type: docs
weight: 183
url: /id/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) metode


Mendefinisikan suara tersemat untuk efek. Tulis [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## Keterangan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Mendapatkan urutan efek untuk slide
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Mengekstrak suara efek dalam array byte
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudio](../../../aspose.slides/iaudio/)
* Kelas [Effect](../)
* RuangNama [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)