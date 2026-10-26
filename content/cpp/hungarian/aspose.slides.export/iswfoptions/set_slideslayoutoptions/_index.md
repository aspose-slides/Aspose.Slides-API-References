---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides C++ API-referencia
description: Beállítja a módot, ahogyan a diák az oldalon elhelyezkednek a prezentáció exportálásakor ISlidesLayoutOptions. Ez a tulajdonság nem támogatja a Aspose.Slides.Export.HandoutLayoutingOptions típusú objektumok hozzárendelését.
type: docs
weight: 404
url: /hu/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metódus


Beállítja a módot, ahogyan a diák az oldalon elhelyezkednek a prezentáció exportálásakor [ISlidesLayoutOptions](../../islideslayoutoptions/). Ez a tulajdonság nem támogatja a **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** típusú objektumok hozzárendelését.

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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
* Osztály [ISwfOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)