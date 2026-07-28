---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides dla C++ - referencja API
description: Określa, czy ukryte slajdy będą eksportowane.
type: docs
weight: 14
url: /pl/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) metoda


Określa, czy ukryte slajdy będą eksportowane.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Zobacz też

* Klasa [IXamlOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export::Xaml](../../)
* Biblioteka [Aspose.Slides](../../../)