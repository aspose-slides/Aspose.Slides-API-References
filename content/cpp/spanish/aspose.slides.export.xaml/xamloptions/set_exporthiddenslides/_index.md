---
title: set_ExportHiddenSlides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si las diapositivas ocultas se exportarán.
type: docs
weight: 14
url: /es/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) método


Determina si las diapositivas ocultas se exportarán.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Véase también

* Clase [XamlOptions](../)
* Espacio de nombres [Aspose::Slides::Export::Xaml](../../)
* Biblioteca [Aspose.Slides](../../../)