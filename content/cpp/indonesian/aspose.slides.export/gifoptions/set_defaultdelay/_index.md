---
title: set_DefaultDelay()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menetapkan waktu tunda default [ms]. Nilai ini akan digunakan jika metode ISlideShowTransition::set_AdvanceAfterTime() tidak dipanggil. Nilai default adalah 1000."
type: docs
weight: 92
url: /id/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) metode

Menetapkan waktu tunda default [ms]. Nilai ini akan digunakan jika [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) metode tidak dipanggil. Nilai default adalah 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
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
* Perpustakaan [Aspose.Slides](../../../)