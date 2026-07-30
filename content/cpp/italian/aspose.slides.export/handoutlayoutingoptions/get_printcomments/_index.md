---
title: get_PrintComments()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica se visualizzare o meno i commenti nelle diapositive
type: docs
weight: 79
url: /it/aspose.slides.export/handoutlayoutingoptions/get_printcomments/
---
## HandoutLayoutingOptions::get_PrintComments() const metodo


Specifica se visualizzare o meno i commenti nelle diapositive

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintComments() const
```

## Osservazioni


Il valore predefinito è **false**. 

Esempio: 
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

## Vedi anche

* Classe [HandoutLayoutingOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)