---
title: set_AdvanceAfter()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah slideshow akan berpindah ke slide berikutnya setelah waktu tertentu. Tulis bool.
type: docs
weight: 118
url: /id/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) metode


Atribut ini menentukan apakah slideshow akan berpindah ke slide berikutnya setelah waktu tertentu. Tulis **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Dapatkan Transisi slide pertama
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Periksa apakah flag Advance Slide After sudah diaktifkan
if (slideTransition->get_AdvanceAfter())
{
    // Dapatkan nilai waktu Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Lihat Juga

* Kelas [SlideShowTransition](../)
* Ruang Nama [Aspose::Slides::SlideShow](../../)
* Perpustakaan [Aspose.Slides](../../../)