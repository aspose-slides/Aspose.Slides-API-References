---
title: get_StopPreviousSound()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. Baca bool.
type: docs
weight: 196
url: /id/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() metode


Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Catatan


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan efek pertama dari slide pertama.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Dapatkan efek pertama dari slide kedua.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Ubah efek kedua Enhancements/Sound menjadi "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Lihat Juga

* Kelas [IEffect](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)