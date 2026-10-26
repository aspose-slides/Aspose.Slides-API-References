---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om dolda bilder ska exporteras.
type: docs
weight: 1
url: /sv/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() metod


Bestämmer om dolda bilder kommer att exporteras.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Se även

* Klass [XamlOptions](../)
* Namnområde [Aspose::Slides::Export::Xaml](../../)
* Bibliotek [Aspose.Slides](../../../)