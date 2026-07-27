---
title: get_PrintComments()
second_title: Referência da API Aspose.Slides para C++
description: Especifica se deve ou não exibir comentários nos slides
type: docs
weight: 79
url: /pt/aspose.slides.export/handoutlayoutingoptions/get_printcomments/
---
## HandoutLayoutingOptions::get_PrintComments() const método


Especifica se deve ou não exibir comentários nos slides

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintComments() const
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

## Ver também

* Classe [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)