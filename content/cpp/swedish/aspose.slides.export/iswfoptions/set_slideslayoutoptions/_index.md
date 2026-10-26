---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in läget där bilder placeras på sidan när en presentation exporteras med ISlidesLayoutOptions. Denna egenskap stöder inte tilldelning av objekt av typen Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 404
url: /sv/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metod

Ställer in läget där bilderna placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../islideslayoutoptions/). Denna egenskap stödjer inte tilldelning av objekt av typen **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klass [ISwfOptions](../)
* Namnområde [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)