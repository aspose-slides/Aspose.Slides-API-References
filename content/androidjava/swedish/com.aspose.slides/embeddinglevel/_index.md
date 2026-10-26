---
title: EmbeddingLevel
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar licensrättigheterna för inbäddning av teckensnittet.
type: docs
url: /sv/com.aspose.slides/embeddinglevel/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Representerar licensrättigheterna för inbäddning av teckensnittet.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Installable](#Installable) | Teckensnitt med denna inställning indikerar att de kan inbäddas och permanent installeras på fjärrsystemet av en applikation. |
| [Restricted](#Restricted) | Teckensnitt som endast har denna bit satt får inte modifieras, inbäddas eller utbytas på något sätt utan att först inhämta tillstånd från den juridiska ägaren. |
| [PreviewPrint](#PreviewPrint) | När denna bit är satt kan teckensnittet inbäddas och tillfälligt laddas på fjärrsystemet. |
| [Editable](#Editable) | När denna bit är satt kan teckensnittet inbäddas men måste endast installeras tillfälligt på andra system. |
| [NoSubsetting](#NoSubsetting) | När denna bit är satt får teckensnittet inte delmängdas före inbäddning. |
| [BitmapOnly](#BitmapOnly) | När denna bit är satt får endast bitmaps som finns i teckensnittet inbäddas. |
### Installerbar {#Installable}
```
public static final int Installable
```


Teckensnitt med denna inställning indikerar att de kan inbäddas och permanent installeras på fjärrsystemet av en applikation. Användaren av fjärrsystemet förvärvar identiska rättigheter, förpliktelser och licenser för det teckensnittet som den ursprungliga köparen, och är föremål för samma slutanvändarlicensavtal, upphovsrätt, designpatent och/eller varumärke som den ursprungliga köparen.

### Begränsad {#Restricted}
```
public static final int Restricted
```


Teckensnitt som endast har denna bit satt får inte modifieras, inbäddas eller utbytas på något sätt utan att först inhämta tillstånd från den juridiska ägaren.

### FörhandsgranskningUtskrift {#PreviewPrint}
```
public static final int PreviewPrint
```


När denna bit är satt kan teckensnittet inbäddas och tillfälligt laddas på fjärrsystemet. Dokument som innehåller Förhandsgranskning- och Utskrifts-teckensnitt måste öppnas "read-only;" inga ändringar kan göras i dokumentet.

### Redigerbar {#Editable}
```
public static final int Editable
```


När denna bit är satt kan teckensnittet inbäddas men måste endast installeras tillfälligt på andra system. Till skillnad från Förhandsgranskning- och Utskrifts-teckensnitt kan dokument som innehåller Redigerbara teckensnitt öppnas för läsning, redigering är tillåten och ändringar kan sparas.

### IngenDeluppsättning {#NoSubsetting}
```
public static final int NoSubsetting
```


När denna bit är satt får teckensnittet inte delmängdas före inbäddning. Andra inbäddningsrestriktioner angivna i bitarna 0-3 och 9 gäller också.

### EndastBitmap {#BitmapOnly}
```
public static final int BitmapOnly
```


När denna bit är satt får endast bitmaps som finns i teckensnittet inbäddas. Ingen konturdata får inbäddas. Om inga bitmaps finns tillgängliga i teckensnittet anses teckensnittet vara oinbäddningsbart och inbäddningstjänsterna kommer att misslyckas.