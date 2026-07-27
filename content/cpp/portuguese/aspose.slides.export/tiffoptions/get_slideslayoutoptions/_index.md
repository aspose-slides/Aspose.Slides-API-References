---
title: get_SlidesLayoutOptions()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o modo em que os slides são colocados na página ao exportar uma apresentação ISlidesLayoutOptions.
type: docs
weight: 170
url: /pt/aspose.slides.export/tiffoptions/get_slideslayoutoptions/
---
## TiffOptions::get_SlidesLayoutOptions() método

Obtém o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::TiffOptions::get_SlidesLayoutOptions() override
```

## Observações

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)