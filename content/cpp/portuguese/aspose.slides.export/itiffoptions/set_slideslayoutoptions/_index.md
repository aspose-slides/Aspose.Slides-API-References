---
title: set_SlidesLayoutOptions()
second_title: Referência da API Aspose.Slides para C++
description: Define o modo como os slides são posicionados na página ao exportar uma apresentação ISlidesLayoutOptions.
type: docs
weight: 170
url: /pt/aspose.slides.export/itiffoptions/set_slideslayoutoptions/
---
## ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) método


Define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)