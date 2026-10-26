---
title: EmbeddingLevel
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de licentierechten voor voor het insluiten van het lettertype.
type: docs
weight: 5786
url: /nl/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Stelt de licentierechten voor voor het insluiten van het lettertype.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) met deze instelling geeft aan dat ze kunnen worden ingesloten en permanent geïnstalleerd op het externe systeem door een toepassing. De gebruiker van het externe systeem verkrijgt dezelfde rechten, verplichtingen en licenties voor dat lettertype als de oorspronkelijke koper van het lettertype, en is onderworpen aan dezelfde eindgebruikerslicentieovereenkomst, auteursrecht, ontwerppatent en/of handelsmerk als de oorspronkelijke koper. |
| Restricted | 2 | [Fonts](../fonts/) die alleen deze bit hebben ingesteld mogen niet worden gewijzigd, ingesloten of op enige wijze uitgewisseld zonder eerst toestemming van de wettelijke eigenaar te verkrijgen. |
| PreviewPrint | 4 | Wanneer deze bit is ingesteld, mag het lettertype worden ingesloten en tijdelijk worden geladen op het externe systeem. Documenten die Preview & Print-lettertypen bevatten moeten in \"alleen-lezen;\" worden geopend; er mogen geen bewerkingen op het document worden toegepast. |
| Editable | 8 | Wanneer deze bit is ingesteld, mag het lettertype worden ingesloten maar mag het alleen tijdelijk op andere systemen worden geïnstalleerd. In tegenstelling tot Preview & Print-lettertypen mogen documenten die Editable-lettertypen bevatten worden geopend voor lezen, bewerken is toegestaan, en wijzigingen kunnen worden opgeslagen. |
| NoSubsetting | 256 | Wanneer deze bit is ingesteld, mag het lettertype niet worden onderverdeeld vóór het insluiten. Andere insluitingsrestricties gespecificeerd in bits 0-3 en 9 zijn ook van toepassing. |
| BitmapOnly | 512 | Wanneer deze bit is ingesteld, mogen alleen bitmaps die in het lettertype aanwezig zijn, worden ingesloten. Er mogen geen omtrekgegevens worden ingesloten. Als er geen bitmaps beschikbaar zijn in het lettertype, wordt het lettertype als niet-insluitbaar beschouwd en zullen de insluitingsservices falen. |

## Zie ook

* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)