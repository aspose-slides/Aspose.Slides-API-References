---
title: get_ExportHiddenSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le diapositive nascoste verranno esportate.
type: docs
weight: 1
url: /it/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() metodo


Determina se le diapositive nascoste verranno esportate.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Vedi anche

* Classe [XamlOptions](../)
* Spazio dei nomi [Aspose::Slides::Export::Xaml](../../)
* Libreria [Aspose.Slides](../../../)