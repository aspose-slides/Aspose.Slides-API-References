---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie ISlidesLayoutOptions. Deze eigenschap ondersteunt het toewijzen van objecten van het type Aspose.Slides.Export.HandoutLayoutingOptions niet.
type: docs
weight: 404
url: /nl/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) methode

Stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../islideslayoutoptions/). Deze eigenschap ondersteunt het toewijzen van objecten van type **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** niet.

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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
* Namespace [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)