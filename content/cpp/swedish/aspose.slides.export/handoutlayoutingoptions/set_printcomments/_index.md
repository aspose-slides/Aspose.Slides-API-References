---
title: set_PrintComments()
second_title: Aspose.Slides för C++ API-referens
description: Anger om kommentarer ska visas på bilderna
type: docs
weight: 92
url: /sv/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) metod


Anger om kommentarer ska visas på bilderna

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## Anmärkningar


Standardvärdet är **false**. 

Exempel: 
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

## Se även

* Klass [HandoutLayoutingOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)