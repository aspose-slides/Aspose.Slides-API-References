---
title: get_ExportHiddenSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah slide tersembunyi akan diekspor.
type: docs
weight: 1
url: /id/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() method


Menentukan apakah slide tersembunyi akan diekspor.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Lihat Juga

* Kelas [IXamlOptions](../)
* Ruang Nama [Aspose::Slides::Export::Xaml](../../)
* Pustaka [Aspose.Slides](../../../)