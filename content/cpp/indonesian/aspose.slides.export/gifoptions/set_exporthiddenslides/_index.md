---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ Referensi API
description: Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.
type: docs
weight: 40
url: /id/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) metode


Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lihat Juga

* Kelas [GifOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)