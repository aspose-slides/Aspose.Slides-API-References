---
title: set_SlidesLayoutOptions()
second_title: Referência da API Aspose.Slides para C++
description: Define o modo como os slides são posicionados na página ao exportar uma apresentação ISlidesLayoutOptions.
type: docs
weight: 378
url: /pt/aspose.slides.export/ipdfoptions/set_slideslayoutoptions/
---
## IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method

Define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Observações

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [IPdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)