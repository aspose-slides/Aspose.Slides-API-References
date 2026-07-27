---
title: get_Handout()
second_title: Referência da API Aspose.Slides para C++
description: Especifica quantos slides e em que sequência serão colocados na página HandoutType.
type: docs
weight: 1
url: /pt/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const método

Especifica quantos slides e em que sequência serão colocados na página [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Observações

O valor padrão é **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Veja Também

* Enum [HandoutType](../../handouttype/)
* Classe [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)