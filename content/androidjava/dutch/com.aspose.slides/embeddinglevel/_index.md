---
title: EmbeddingLevel
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt de licentierechten voor het insluiten van het lettertype.
type: docs
url: /nl/com.aspose.slides/embeddinglevel/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Vertegenwoordigt de licentierechten voor het insluiten van het lettertype.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Installable](#Installable) | Lettertypen met deze instelling geven aan dat ze kunnen worden ingesloten en permanent geïnstalleerd op het externe systeem door een applicatie. |
| [Restricted](#Restricted) | Lettertypen waarbij alleen dit bit is ingesteld, mogen niet worden gewijzigd, ingesloten of uitgewisseld op welke manier dan ook zonder eerst toestemming van de rechtsmatige eigenaar te verkrijgen. |
| [PreviewPrint](#PreviewPrint) | Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten en tijdelijk worden geladen op het externe systeem. |
| [Editable](#Editable) | Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten, maar moet het alleen tijdelijk worden geïnstalleerd op andere systemen. |
| [NoSubsetting](#NoSubsetting) | Wanneer dit bit is ingesteld, mag het lettertype niet worden onderverdeeld vóór het insluiten. |
| [BitmapOnly](#BitmapOnly) | Wanneer dit bit is ingesteld, mogen alleen bitmapafbeeldingen die in het lettertype zijn opgenomen, worden ingesloten. |
### Installeerbaar {#Installable}
```
public static final int Installable
```

Lettertypen met deze instelling geven aan dat ze kunnen worden ingesloten en permanent geïnstalleerd op het externe systeem door een applicatie. De gebruiker van het externe systeem verkrijgt dezelfde rechten, verplichtingen en licenties voor dat lettertype als de oorspronkelijke koper van het lettertype, en is onderworpen aan dezelfde eindgebruikerslicentieovereenkomst, auteursrecht, ontwerp-patent en/of handelsmerk als de oorspronkelijke koper.

### Beperkt {#Restricted}
```
public static final int Restricted
```

Lettertypen waarbij alleen dit bit is ingesteld, mogen niet worden gewijzigd, ingesloten of uitgewisseld op welke manier dan ook zonder eerst toestemming van de rechtsmatige eigenaar te verkrijgen.

### VoorbeeldAfdruk {#PreviewPrint}
```
public static final int PreviewPrint
```

Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten en tijdelijk worden geladen op het externe systeem. Documenten die Preview- & Print-lettertypen bevatten, moeten in "alleen-lezen" worden geopend; er kunnen geen bewerkingen op het document worden toegepast.

### Bewerkbaar {#Editable}
```
public static final int Editable
```

Wanneer dit bit is ingesteld, mag het lettertype worden ingesloten, maar moet het alleen tijdelijk worden geïnstalleerd op andere systemen. In tegenstelling tot Preview- & Print-lettertypen, mogen documenten die Bewerkbare lettertypen bevatten, worden geopend voor lezen; bewerken is toegestaan en wijzigingen kunnen worden opgeslagen.

### GeenSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Wanneer dit bit is ingesteld, mag het lettertype niet worden onderverdeeld vóór het insluiten. Andere insluitingsbeperkingen die zijn gespecificeerd in bits 0-3 en 9 zijn ook van toepassing.

### AlleenBitmap {#BitmapOnly}
```
public static final int BitmapOnly
```

Wanneer dit bit is ingesteld, mogen alleen bitmapafbeeldingen die in het lettertype zijn opgenomen, worden ingesloten. Er mogen geen omtrek-gegevens worden ingesloten. Als er geen bitmapafbeeldingen beschikbaar zijn in het lettertype, wordt het lettertype beschouwd als niet-insluitbaar en zullen de insluitingsservices falen.