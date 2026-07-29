---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om dolda bilder ska exporteras.
type: docs
weight: 14
url: /sv/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) metod


Bestämmer om dolda bilder ska exporteras.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Se även

* Klass [IXamlOptions](../)
* Namnrymd [Aspose::Slides::Export::Xaml](../../)
* Bibliotek [Aspose.Slides](../../../)