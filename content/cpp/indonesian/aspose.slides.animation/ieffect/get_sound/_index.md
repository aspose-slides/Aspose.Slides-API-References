---
title: get_Sound()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan suara tersemat untuk efek. Baca IAudio.
type: docs
weight: 170
url: /id/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() metode

Mendefinisikan suara tersemat untuk efek. Baca [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
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
* Kelas [IEffect](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)