---
title: set_StopPreviousSound()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. Tulis bool.
type: docs
weight: 209
url: /id/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) metode


Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. Tulis **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## Keterangan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan efek pertama pada slide pertama.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Dapatkan efek pertama pada slide kedua.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Ubah Enhancements/Sound efek kedua menjadi "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Lihat Juga

* Kelas [Effect](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)