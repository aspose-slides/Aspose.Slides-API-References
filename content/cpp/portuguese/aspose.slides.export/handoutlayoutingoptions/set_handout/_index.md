---
title: set_Handout()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica quantos slides e em que sequência serão colocados na página HandoutType.
type: docs
weight: 14
url: /pt/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) método

Especifica quantos slides e em que sequência serão colocados na página [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
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

## Ver Também

* Enum [HandoutType](../../handouttype/)
* Classe [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)