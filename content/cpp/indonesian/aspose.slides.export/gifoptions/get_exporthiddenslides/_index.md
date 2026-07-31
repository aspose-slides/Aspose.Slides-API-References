---
title: get_ExportHiddenSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.
type: docs
weight: 27
url: /id/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() metode

Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
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
* Namespace [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)