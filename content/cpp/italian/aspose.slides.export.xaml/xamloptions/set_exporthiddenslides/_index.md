---
title: set_ExportHiddenSlides()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le diapositive nascoste saranno esportate.
type: docs
weight: 14
url: /it/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) metodo


Determina se le diapositive nascoste saranno esportate.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
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