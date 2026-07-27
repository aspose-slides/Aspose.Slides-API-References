---
title: get_ExportHiddenSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se os slides ocultos serão exportados.
type: docs
weight: 1
url: /pt/aspose.slides.export.xaml/ixamloptions/get_exporthiddenslides/
---
## IXamlOptions::get_ExportHiddenSlides() método


Determina se os slides ocultos serão exportados.

```cpp
virtual bool Aspose::Slides::Export::Xaml::IXamlOptions::get_ExportHiddenSlides()=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Veja Também

* Classe [IXamlOptions](../)
* Namespace [Aspose::Slides::Export::Xaml](../../)
* Biblioteca [Aspose.Slides](../../../)