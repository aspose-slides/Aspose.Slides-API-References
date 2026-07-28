---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides dla C++ - odwołanie API
description: Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji ISlidesLayoutOptions. Ta właściwość nie obsługuje przypisywania obiektów typu HandoutLayoutingOptions
type: docs
weight: 404
url: /pl/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metoda

Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../islideslayoutoptions/). Ta właściwość nie obsługuje przypisywania obiektów typu [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [SwfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)