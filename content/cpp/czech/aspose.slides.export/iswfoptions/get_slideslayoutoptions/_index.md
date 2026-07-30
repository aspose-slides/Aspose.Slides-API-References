---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ API Reference
description: Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace ISlidesLayoutOptions. Tato vlastnost nepodporuje přiřazování objektů typu Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 391
url: /cs/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() metoda

Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/). Tato vlastnost nepodporuje přiřazování objektů typu **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
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
* Třída [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Třída [ISwfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)