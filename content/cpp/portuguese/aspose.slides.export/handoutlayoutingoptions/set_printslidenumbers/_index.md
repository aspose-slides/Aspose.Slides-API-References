---
title: set_PrintSlideNumbers()
second_title: Referência da API Aspose.Slides para C++
description: Especifica se deve ou não imprimir os números dos slides exibidos.
type: docs
weight: 40
url: /pt/aspose.slides.export/handoutlayoutingoptions/set_printslidenumbers/
---
## HandoutLayoutingOptions::set_PrintSlideNumbers(bool) método

Especifica se deve ou não imprimir os números dos slides exibidos.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintSlideNumbers(bool value)
```

## Observações

O valor padrão é **true**. 

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Veja Também

* Classe [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)