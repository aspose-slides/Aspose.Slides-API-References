---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekérdezi a diák oldalra helyezésének módját a prezentáció exportálásakor ISlidesLayoutOptions. Ez a tulajdonság nem támogatja a HandoutLayoutingOptions típusú objektumok hozzárendelését.
type: docs
weight: 391
url: /hu/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() metódus

Lekérdezi a diák oldalra helyezésének módját a bemutató exportálásakor [ISlidesLayoutOptions](../../islideslayoutoptions/). Ez a tulajdonság nem támogatja a [HandoutLayoutingOptions](../../handoutlayoutingoptions/) típusú objektumok hozzárendelését

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [ISlidesLayoutOptions](../../islideslayoutoptions/)
* osztály [SwfOptions](../)
* névtér [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)