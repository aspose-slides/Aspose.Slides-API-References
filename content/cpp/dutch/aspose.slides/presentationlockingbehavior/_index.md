---
title: PresentationLockingBehavior
second_title: Aspose.Slides voor C++ API-referentie
description: "Geeft het gedrag weer met betrekking tot de behandeling van de IPresentation bron (bestand of System::IO::Stream) tijdens het laden en werken met een instantie van IPresentation."
type: docs
weight: 6748
url: /nl/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Geeft het gedrag weer met betrekking tot de behandeling van de [IPresentation](../ipresentation/) bron (bestand of [System::IO::Stream](../../system.io/stream/)) tijdens het laden en werken met een instantie van [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| LoadAndRelease | 0 | De bron wordt alleen vergrendeld gedurende de uitvoering van de [IPresentation](../ipresentation/) constructor. |
| KeepLocked | 1 | De bron wordt vergrendeld gedurende de hele levensduur van de [IPresentation](../ipresentation/)-instantie, totdat deze wordt vrijgegeven. |

## Opmerkingen

De bron is de parameter die aan de [IPresentation](../ipresentation/) constructor wordt doorgegeven. In het onderstaande voorbeeld is de bron het bestand "pres.pptx": 

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Voor dit voorbeeld zal de bron ("pres.pptx"-bestand) vergrendeld zijn gedurende de levensduur van een [IPresentation](../ipresentation/)-instantie, d.w.z. deze kan niet worden gewijzigd of verwijderd door een ander proces. 

## Zie ook

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)