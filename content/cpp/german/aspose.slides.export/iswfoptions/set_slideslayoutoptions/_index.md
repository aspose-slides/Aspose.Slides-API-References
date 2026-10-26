---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt den Modus fest, in dem Folien beim Export einer Präsentation auf die Seite gelegt werden ISlidesLayoutOptions. Diese Eigenschaft unterstützt das Zuweisen von Objekten des Typs Aspose.Slides.Export.HandoutLayoutingOptions nicht.
type: docs
weight: 404
url: /de/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) Methode

Legt den Modus fest, in dem Folien beim Export einer Präsentation auf die Seite gelegt werden [ISlidesLayoutOptions](../../islideslayoutoptions/). Diese Eigenschaft unterstützt das Zuweisen von Objekten vom Typ **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** nicht.

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Anmerkungen

Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasse [ISwfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)