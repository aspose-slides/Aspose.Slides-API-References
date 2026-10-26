---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enumeratie

Geeft de licentierechten weer voor het insluiten van het lettertype.

Het type EmbeddingLevel geeft de volgende leden weer:

## Velden

| Veld | Beschrijving |
| :- | :- |
| INSTALLABLE | Lettertypen met deze instelling geven aan dat ze mogen worden ingebed en permanent geïnstalleerd op het externe systeem door een applicatie.<br/>De gebruiker van het externe systeem verkrijft dezelfde rechten, verplichtingen en licenties voor dat lettertype als de oorspronkelijke koper van het lettertype,<br/>en is onderworpen aan dezelfde eindgebruikerslicentieovereenkomst, auteursrecht, ontwerp-patent en/of handelsmerk als de oorspronkelijke koper. |
| RESTRICTED | Lettertypen die alleen deze bit hebben ingesteld mogen niet worden gewijzigd, ingebed of op enige manier uitgewisseld zonder eerst toestemming van de wettelijke eigenaar te verkrijgen. |
| PREVIEW_PRINT | Wanneer dit bit is ingesteld, mag het lettertype worden ingebed en tijdelijk worden geladen op het externe systeem. Documenten die Preview &<br/>Print-lettertypen bevatten moeten in "read-only" worden geopend; er mogen geen bewerkingen op het document worden toegepast. |
| EDITABLE | Wanneer dit bit is ingesteld, mag het lettertype worden ingebed maar moet het alleen tijdelijk op andere systemen worden geïnstalleerd. In tegenstelling tot Preview &<br/>Print-lettertypen, mogen documenten die Editable-lettertypen bevatten worden geopend voor lezen, bewerken is toegestaan, en wijzigingen mogen worden opgeslagen. |
| NO_SUBSETTING | Wanneer dit bit is ingesteld, mag het lettertype niet worden onderverdeeld vóór het insluiten. Andere insluitingsbeperkingen gespecificeerd in bits 0-3 en 9 zijn ook van toepassing. |
| BITMAP_ONLY | Wanneer dit bit is ingesteld, mogen alleen bitmap-afbeeldingen die in het lettertype zijn opgenomen, worden ingebed. Er mogen geen outline-gegevens worden ingebed. Als er geen bitmap-afbeeldingen beschikbaar zijn in het lettertype,<br/>dan wordt het lettertype beschouwd als niet-inbedbaar en zullen de insluitingsservices mislukken. |

### Zie Ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)