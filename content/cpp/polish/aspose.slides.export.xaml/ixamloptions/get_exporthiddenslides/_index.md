---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa, czy ukryte slajdy będą eksportowane.
type: docs
weight: 1
url: /pl/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() metoda

Określa, czy ukryte slajdy będą eksportowane.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Zobacz także

* Klasa [IXamlOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export::Xaml](../../)
* Biblioteka [Aspose.Slides](../../../)