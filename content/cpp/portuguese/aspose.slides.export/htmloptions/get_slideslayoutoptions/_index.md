---
title: get_SlidesLayoutOptions()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o modo em que os slides são posicionados na página ao exportar uma apresentação ISlidesLayoutOptions.
type: docs
weight: 1
url: /pt/aspose.slides.export/htmloptions/get_slideslayoutoptions/
---
## HtmlOptions::get_SlidesLayoutOptions() método


Obtém o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::HtmlOptions::get_SlidesLayoutOptions() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [HtmlOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)