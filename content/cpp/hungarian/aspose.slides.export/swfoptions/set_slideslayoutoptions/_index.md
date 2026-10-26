---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides C++ API referenciája
description: Beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor ISlidesLayoutOptions. Ez a tulajdonság nem támogatja a HandoutLayoutingOptions típusú objektumok hozzárendelését.
type: docs
weight: 404
url: /hu/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metódus

Beállítja a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../islideslayoutoptions/). Ez a tulajdonság nem támogatja az [HandoutLayoutingOptions](../../handoutlayoutingoptions/) típusú objektumok hozzárendelését.

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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
* Osztály [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Osztály [SwfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)