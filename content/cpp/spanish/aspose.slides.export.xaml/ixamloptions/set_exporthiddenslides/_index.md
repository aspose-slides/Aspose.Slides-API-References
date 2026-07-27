---
title: set_ExportHiddenSlides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si las diapositivas ocultas se exportarán.
type: docs
weight: 14
url: /es/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) método


Determina si las diapositivas ocultas se exportarán.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
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
* Biblioteca [Aspose.Slides](../../../)