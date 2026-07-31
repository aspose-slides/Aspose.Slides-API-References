---
title: get_DefaultDelay()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan waktu tunda default [ms]. Nilai ini akan digunakan jika metode ISlideShowTransition::set_AdvanceAfterTime() tidak dipanggil. Nilai defaultnya adalah 1000."
type: docs
weight: 79
url: /id/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() metode

Mendapatkan waktu tunda default [ms]. Nilai ini akan digunakan jika metode [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) tidak dipanggil. Nilai defaultnya adalah 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Lihat Juga

* Kelas [IGifOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)