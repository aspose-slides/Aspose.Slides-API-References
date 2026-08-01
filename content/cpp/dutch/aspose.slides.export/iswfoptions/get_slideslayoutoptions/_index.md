---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie ISlidesLayoutOptions. Deze eigenschap ondersteunt het toewijzen van objecten van het type Aspose.Slides.Export.HandoutLayoutingOptions niet.
type: docs
weight: 391
url: /nl/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() methode


Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../islideslayoutoptions/). Deze eigenschap ondersteunt het toewijzen van objecten van het type **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** niet.

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klasse [ISwfOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)