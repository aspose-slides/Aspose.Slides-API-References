---
title: get_PrintSlideNumbers()
second_title: Aspose.Slides för C++ API-referens
description: Anger om de visade bildnumren ska skrivas ut eller inte.
type: docs
weight: 27
url: /sv/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const metod


Anger om de visade bildnumren ska skrivas ut eller inte.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## Anmärkningar


Standardvärdet är **true**. 

Exempel: 
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

## Se även

* Klass [HandoutLayoutingOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)