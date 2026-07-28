---
title: get_PrintComments()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy wyświetlać komentarze na slajdach
type: docs
weight: 79
url: /pl/aspose.slides.export/handoutlayoutingoptions/get_printcomments/
---
## HandoutLayoutingOptions::get_PrintComments() const metoda

Określa, czy wyświetlać komentarze na slajdach

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintComments() const
```

## Uwagi

Domyślna wartość to **false**. 

Przykład: 
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

## Zobacz także

* Klasa [HandoutLayoutingOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)