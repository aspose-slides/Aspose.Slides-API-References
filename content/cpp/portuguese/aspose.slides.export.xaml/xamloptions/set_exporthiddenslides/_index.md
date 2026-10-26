---
title: set_ExportHiddenSlides()
second_title: Referência da API Aspose.Slides para C++
description: Determina se os slides ocultos serão exportados.
type: docs
weight: 14
url: /pt/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) método


Determina se os slides ocultos serão exportados.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Veja Também

* Classe [XamlOptions](../)
* Espaço de nomes [Aspose::Slides::Export::Xaml](../../)
* Biblioteca [Aspose.Slides](../../../)