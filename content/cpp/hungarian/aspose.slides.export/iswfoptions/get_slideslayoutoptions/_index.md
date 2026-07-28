---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API referencia
description: Megkapja a módot, amelyben a diák az oldalon kerülnek elhelyezésre egy prezentáció exportálásakor ISlidesLayoutOptions. Ez a tulajdonság nem támogatja a Aspose.Slides.Export.HandoutLayoutingOptions típusú objektumok hozzárendelését
type: docs
weight: 391
url: /hu/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() metódus


A módot adja vissza, amelyben a diák az oldalon helyezkednek el a prezentáció exportálásakor [ISlidesLayoutOptions](../../islideslayoutoptions/). Ez a tulajdonság nem támogatja a **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** típusú objektumok hozzárendelését.

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
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
* Névtér [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)