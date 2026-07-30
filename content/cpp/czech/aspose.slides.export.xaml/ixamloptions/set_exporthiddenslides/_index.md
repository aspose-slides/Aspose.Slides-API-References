---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda budou skryté snímky exportovány.
type: docs
weight: 14
url: /cs/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) metoda

Určuje, zda budou skryté snímky exportovány.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Poznámky


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```


## Viz také

* Třída [IXamlOptions](../)
* Jmenný prostor [Aspose::Slides::Export::Xaml](../../)
* Knihovna [Aspose.Slides](../../../)