---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace ISlidesLayoutOptions. Tato vlastnost nepodporuje přiřazování objektů typu Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 404
url: /cs/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metoda


Nastavuje režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/). Tato vlastnost nepodporuje přiřazování objektů typu **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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
* třída [ISwfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)