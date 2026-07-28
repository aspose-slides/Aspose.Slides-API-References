---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji ISlidesLayoutOptions. Ta właściwość nie obsługuje przypisywania obiektów typu HandoutLayoutingOptions
type: docs
weight: 391
url: /pl/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() metoda

Zwraca tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/). Ta właściwość nie obsługuje przypisywania obiektów typu [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasa [SwfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)