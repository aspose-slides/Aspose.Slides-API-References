---
title: get_ExportHiddenSlides()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si las diapositivas ocultas se exportarán.
type: docs
weight: 1
url: /es/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() método


Determina si las diapositivas ocultas se exportarán.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Ver también

* Clase [XamlOptions](../)
* Espacio de nombres [Aspose::Slides::Export::Xaml](../../)
* Biblioteca [Aspose.Slides](../../../)