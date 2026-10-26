---
title: EmbeddingLevel
second_title: Aspose.Slides för Java API-referens
description: Representerar licensrättigheterna för att bädda in typsnittet.
type: docs
url: /sv/com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Representerar licensrättigheterna för inbäddning av typsnittet.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Installable](#Installable) | Typsnitt med denna inställning indikerar att de kan bäddas in och installeras permanent på fjärrsystemet av en applikation. |
| [Restricted](#Restricted) | Typsnitt som endast har denna bit inställd får inte modifieras, bäddas in eller utbytas på något sätt utan att först erhålla tillstånd från den juridiska ägaren. |
| [PreviewPrint](#PreviewPrint) | När denna bit är inställd kan typsnittet bäddas in och tillfälligt laddas på fjärrsystemet. |
| [Editable](#Editable) | När denna bit är inställd kan typsnittet bäddas in men får endast installeras tillfälligt på andra system. |
| [NoSubsetting](#NoSubsetting) | När denna bit är inställd får typsnittet inte delmängdsindelas innan inbäddning. |
| [BitmapOnly](#BitmapOnly) | När denna bit är inställd får endast bitmap-bilder som finns i typsnittet bäddas in. |
### Installable {#Installable}
```
public static final int Installable
```

Typsnitt med denna inställning indikerar att de kan bäddas in och installeras permanent på fjärrsystemet av en applikation. Användaren av fjärrsystemet erhåller samma rättigheter, skyldigheter och licenser för det typsnittet som den ursprungliga köparen av typsnittet, och är bunden av samma slutanvändarlicensavtal, upphovsrätt, designpatent och/eller varumärke som den ursprungliga köparen.

### Restricted {#Restricted}
```
public static final int Restricted
```

Typsnitt som endast har denna bit inställd får inte modifieras, bäddas in eller utbytas på något sätt utan att först erhålla tillstånd från den juridiska ägaren.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

När denna bit är inställd kan typsnittet bäddas in och tillfälligt laddas på fjärrsystemet. Dokument som innehåller Preview & Print-typsnitt måste öppnas i "read-only"; inga ändringar kan göras i dokumentet.

### Editable {#Editable}
```
public static final int Editable
```

När denna bit är inställd kan typsnittet bäddas in men får endast installeras tillfälligt på andra system. Till skillnad från Preview & Print-typsnitt kan dokument som innehåller Editable-typsnitt öppnas för läsning, redigering är tillåten och ändringar kan sparas.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

När denna bit är inställd får typsnittet inte delmängdsindelas innan inbäddning. Andra inbäddningsrestriktioner som specificeras i bitarna 0-3 och 9 gäller också.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

När denna bit är inställd får endast bitmap-bilder som finns i typsnittet bäddas in. Inga konturdata får inbäddas. Om det inte finns några bitmap-bilder i typsnittet anses typsnittet vara icke-inbäddningsbart och inbäddningstjänsterna kommer att misslyckas.