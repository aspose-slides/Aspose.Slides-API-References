---
title: get_ExportHiddenSlides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si las diapositivas ocultas se exportarán.
type: docs
weight: 1
url: /es/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() método

Determina si las diapositivas ocultas se exportarán.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Ver también

* Clase [IXamlOptions](../)
* Espacio de nombres [Aspose::Slides::Export::Xaml](../../)
* Library [Aspose.Slides](../../../)