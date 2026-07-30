---
title: get_Handout()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica quanti slide e in quale sequenza saranno collocati sulla pagina HandoutType.
type: docs
weight: 1
url: /it/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const metodo


Specifica quanti slide e in quale sequenza saranno collocati sulla pagina [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Osservazioni


Il valore predefinito è **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Vedi anche

* Enumerazione [HandoutType](../../handouttype/)
* Classe [HandoutLayoutingOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)