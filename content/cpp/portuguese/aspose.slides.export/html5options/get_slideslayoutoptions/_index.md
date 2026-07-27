---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o modo em que os slides são colocados na página ao exportar uma apresentação ISlidesLayoutOptions.
type: docs
weight: 157
url: /pt/aspose.slides.export/html5options/get_slideslayoutoptions/
---
## Html5Options::get_SlidesLayoutOptions() método


Obtém o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::Html5Options::get_SlidesLayoutOptions() override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)