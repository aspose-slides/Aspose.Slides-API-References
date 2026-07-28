---
title: get_PrintSlideNumbers()
second_title: Aspose.Slides dla referencji API C++
description: Określa, czy drukować wyświetlane numery slajdów.
type: docs
weight: 27
url: /pl/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const metoda

Określa, czy drukować wyświetlane numery slajdów.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## Uwagi

Domyślna wartość to **true**. 

Przykład: 
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

## Zobacz także

* Klasa [HandoutLayoutingOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)