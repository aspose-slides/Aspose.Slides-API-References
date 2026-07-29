---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in läget i vilket bilder placeras på sidan när en presentation exporteras ISlidesLayoutOptions. Denna egenskap stöder inte att tilldela objekt av typen HandoutLayoutingOptions
type: docs
weight: 404
url: /sv/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metod

Ställer in läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../islideslayoutoptions/). Denna egenskap stöder inte att tilldela objekt av typen [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klass [SwfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)