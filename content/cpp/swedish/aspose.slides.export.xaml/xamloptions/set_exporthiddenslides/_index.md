---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om dolda bilder ska exporteras.
type: docs
weight: 14
url: /sv/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) metod


Avgör om dolda bilder ska exporteras.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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
* Namnrymd [Aspose::Slides::Export::Xaml](../../)
* Bibliotek [Aspose.Slides](../../../)