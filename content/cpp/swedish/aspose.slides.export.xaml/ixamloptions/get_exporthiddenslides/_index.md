---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om dolda bilder ska exporteras.
type: docs
weight: 1
url: /sv/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() metod


Bestämmer om dolda bilder ska exporteras.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
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