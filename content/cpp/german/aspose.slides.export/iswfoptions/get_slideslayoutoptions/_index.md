---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt den Modus, in dem Folien beim Export einer Präsentation auf der Seite platziert werden ISlidesLayoutOptions. Diese Eigenschaft unterstützt die Zuweisung von Objekten des Typs Aspose.Slides.Export.HandoutLayoutingOptions nicht.
type: docs
weight: 391
url: /de/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() Methode

Ermittelt den Modus, in dem Folien beim Export einer Präsentation auf der Seite platziert werden [ISlidesLayoutOptions](../../islideslayoutoptions/). Diese Eigenschaft unterstützt die Zuweisung von Objekten des Typs **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** nicht.

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
```

## Hinweise

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasse [ISwfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)