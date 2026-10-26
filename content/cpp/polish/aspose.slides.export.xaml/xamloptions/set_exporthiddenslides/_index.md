---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa, czy ukryte slajdy będą eksportowane.
type: docs
weight: 14
url: /pl/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) metoda


Określa, czy ukryte slajdy będą eksportowane.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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