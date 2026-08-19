---
title: EmbeddingLevel
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de licentierechten voor het insluiten van het lettertype voor.
type: docs
url: /nl/com.aspose.slides/embeddinglevel/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Stelt de licentierechten voor het insluiten van het lettertype voor.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Installable](#Installable) | Lettertypen met deze instelling geven aan dat ze kunnen worden ingesloten en permanent geïnstalleerd op het externe systeem door een toepassing. De gebruiker van het externe systeem verkrijgt dezelfde rechten, verplichtingen en licenties voor dat lettertype als de oorspronkelijke koper van het lettertype, en is onderworpen aan dezelfde eindgebruikerslicentieovereenkomst, auteursrecht, designpatent en/of handelsmerk als de oorspronkelijke koper. |
| [Restricted](#Restricted) | Lettertypen die alleen dit bit hebben ingesteld, mogen niet worden gewijzigd, ingesloten of op enige wijze uitgewisseld zonder eerst toestemming te krijgen van de wettelijke eigenaar. |
| [PreviewPrint](#PreviewPrint) | Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten en tijdelijk worden geladen op het externe systeem. |
| [Editable](#Editable) | Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten, maar moet het alleen tijdelijk op andere systemen worden geïnstalleerd. |
| [NoSubsetting](#NoSubsetting) | Wanneer dit bit is ingesteld, mag het lettertype niet worden onderverdeeld (subsettig) vóór het insluiten. |
| [BitmapOnly](#BitmapOnly) | Wanneer dit bit is ingesteld, mogen alleen bitmapafbeeldingen die in het lettertype zijn opgenomen, worden ingesloten. |
### Installeerbaar {#Installable}
```
public static final int Installable
```

Lettertypen met deze instelling geven aan dat ze kunnen worden ingesloten en permanent geïnstalleerd op het externe systeem door een toepassing. De gebruiker van het externe systeem verkrijgt dezelfde rechten, verplichtingen en licenties voor dat lettertype als de oorspronkelijke koper van het lettertype, en is onderworpen aan dezelfde eindgebruikerslicentieovereenkomst, auteursrecht, designpatent en/of handelsmerk als de oorspronkelijke koper.

### Beperkt {#Restricted}
```
public static final int Restricted
```

Lettertypen die alleen dit bit hebben ingesteld, mogen niet worden gewijzigd, ingesloten of op enige wijze uitgewisseld zonder eerst toestemming te krijgen van de wettelijke eigenaar.

### VoorbeeldAfdruk {#PreviewPrint}
```
public static final int PreviewPrint
```

Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten en tijdelijk worden geladen op het externe systeem. Documenten die Preview & Print-lettertypen bevatten, moeten in "read-only"-modus worden geopend; er mogen geen bewerkingen op het document worden toegepast.

### Bewerkbaar {#Editable}
```
public static final int Editable
```

Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten, maar moet het alleen tijdelijk op andere systemen worden geïnstalleerd. In tegenstelling tot Preview & Print-lettertypen, mogen documenten die bewerkbare lettertypen bevatten, worden geopend voor lezen, bewerken is toegestaan, en wijzigingen kunnen worden opgeslagen.

### GeenSubset {#NoSubsetting}
```
public static final int NoSubsetting
```

Wanneer dit bit is ingesteld, mag het lettertype niet worden onderverdeeld (subsettig) vóór het insluiten. Andere insluitingsbeperkingen gespecificeerd in bits 0-3 en 9 zijn ook van toepassing.

### AlleenBitmap {#BitmapOnly}
```
public static final int BitmapOnly
```

Wanneer dit bit is ingesteld, mogen alleen bitmapafbeeldingen die in het lettertype zijn opgenomen, worden ingesloten. Geen omtrekgegevens mogen worden ingesloten. Als er geen bitmapafbeeldingen beschikbaar zijn in het lettertype, wordt het lettertype beschouwd als niet-insluitbaar en zullen de insluitingsdiensten falen.