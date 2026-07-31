---
title: set_AdvanceAfter()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah slideshow akan berpindah ke slide berikutnya setelah waktu tertentu. Tulis bool.
type: docs
weight: 118
url: /id/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) method

Atribut ini menentukan apakah slideshow akan berpindah ke slide berikutnya setelah waktu tertentu. Tulis **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Dapatkan Transisi slide pertama
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Periksa apakah flag Advance Slide After diaktifkan
if (slideTransition->get_AdvanceAfter())
{
    // Dapatkan nilai Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Lihat Juga

* Kelas [ISlideShowTransition](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)