---
title: set_ExportHiddenSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah slide tersembunyi akan diekspor.
type: docs
weight: 14
url: /id/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) metode

Menentukan apakah slide tersembunyi akan diekspor.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Lihat Juga

* Kelas [XamlOptions](../)
* Ruang Nama [Aspose::Slides::Export::Xaml](../../)
* Perpustakaan [Aspose.Slides](../../../)