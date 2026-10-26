---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ Referensi API
description: Menentukan apakah slide tersembunyi akan diekspor.
type: docs
weight: 14
url: /id/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) metode



Menentukan apakah slide tersembunyi akan diekspor.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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