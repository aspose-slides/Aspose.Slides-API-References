---
title: get_ExportHiddenSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.
type: docs
weight: 27
url: /id/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() metode


Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lihat Juga

* Kelas [IGifOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)