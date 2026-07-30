---
title: get_PrintFrameSlide()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica se disegnare le cornici intorno alle diapositive visualizzate o meno.
type: docs
weight: 53
url: /it/aspose.slides.export/handoutlayoutingoptions/get_printframeslide/
---
## HandoutLayoutingOptions::get_PrintFrameSlide() const metodo

Specifica se disegnare le cornici intorno alle diapositive visualizzate o meno.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintFrameSlide() const
```

## Osservazioni

Il valore predefinito è **true**. 

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Vedi anche

* Classe [HandoutLayoutingOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)