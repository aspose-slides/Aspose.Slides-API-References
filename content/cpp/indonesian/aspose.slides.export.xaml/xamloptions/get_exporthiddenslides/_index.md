---
title: get_ExportHiddenSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah slide tersembunyi akan diekspor.
type: docs
weight: 1
url: /id/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() metode


Menentukan apakah slide tersembunyi akan diekspor.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Keterangan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Lihat Juga

* Kelas [XamlOptions](../)
* Ruang Nama [Aspose::Slides::Export::Xaml](../../)
* Pustaka [Aspose.Slides](../../../)