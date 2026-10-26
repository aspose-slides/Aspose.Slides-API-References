---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa, czy ukryte slajdy będą eksportowane.
type: docs
weight: 1
url: /pl/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() metoda


Określa, czy ukryte slajdy będą eksportowane.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Zobacz także

* Klasa [XamlOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export::Xaml](../../)
* Biblioteka [Aspose.Slides](../../../)