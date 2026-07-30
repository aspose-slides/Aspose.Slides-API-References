---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace ISlidesLayoutOptions. Tato vlastnost nepodporuje přiřazování objektů typu HandoutLayoutingOptions
type: docs
weight: 391
url: /cs/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() metoda

Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/). Tato vlastnost nepodporuje přiřazování objektů typu [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [ISlidesLayoutOptions](../../islideslayoutoptions/)
* třída [SwfOptions](../)
* jmenný prostor [Aspose::Slides::Export](../../)
* knihovna [Aspose.Slides](../../../)