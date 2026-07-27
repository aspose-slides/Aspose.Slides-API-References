---
title: get_ExportHiddenSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se os slides ocultos serão exportados.
type: docs
weight: 1
url: /pt/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() método


Determina se os slides ocultos serão exportados.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Veja também

* Classe [XamlOptions](../)
* Namespace [Aspose::Slides::Export::Xaml](../../)
* Biblioteca [Aspose.Slides](../../../)