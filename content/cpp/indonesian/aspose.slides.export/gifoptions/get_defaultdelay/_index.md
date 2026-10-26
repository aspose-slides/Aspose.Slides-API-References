---
title: get_DefaultDelay()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan waktu jeda default [ms]. Nilai ini akan digunakan jika metode ISlideShowTransition::set_AdvanceAfterTime() tidak dipanggil. Nilai default adalah 1000."
type: docs
weight: 79
url: /id/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() metode

Mendapatkan waktu jeda default [ms]. Nilai ini akan digunakan jika metode [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) tidak dipanggil. Nilai default adalah 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Lihat Juga

* Kelas [GifOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)