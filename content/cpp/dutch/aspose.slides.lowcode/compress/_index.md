---
title: Compress
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om Presentation te comprimeren.
type: docs
weight: 14
url: /nl/aspose.slides.lowcode/compress/
---
## Compress klasse

Stelt een groep methoden voor die bedoeld zijn om [Presentation](../../aspose.slides/presentation/) te comprimeren.

```cpp
class Compress
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Voert compressie uit van de [Presentation](../../aspose.slides/presentation/) door ongebruikte tekens uit ingesloten lettertypen te verwijderen. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Voert compressie uit van de [Presentation](../../aspose.slides/presentation/) door ongebruikte lay-out dia's te verwijderen. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Voert compressie uit van de [Presentation](../../aspose.slides/presentation/) door ongebruikte masterdia's te verwijderen. |
## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Naamruimte [Aspose::Slides::LowCode](../)
* Bibliotheek [Aspose.Slides](../../)