---
title: set_PrintComments()
second_title: Referência da API Aspose.Slides para C++
description: Especifica se deve ou não exibir comentários nos slides
type: docs
weight: 92
url: /pt/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) método


Especifica se deve ou não exibir comentários nos slides

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## Observações


O valor padrão é **false**. 

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Veja Também

* Classe [HandoutLayoutingOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)