---
title: set_ExportHiddenSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se os slides ocultos serão exportados.
type: docs
weight: 14
url: /pt/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) método

Determina se os slides ocultos serão exportados.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## Observações


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```


## Ver também

* Classe [IXamlOptions](../)
* Espaço de nomes [Aspose::Slides::Export::Xaml](../../)
* Biblioteca [Aspose.Slides](../../../)