---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een manager voor die het gedrag van de voettekst-, datum-tijd- en paginanummer-plaatsaanduidingen van de lay-out-dia en alle onderliggende plaatsaanduidingen beheert.
type: docs
url: /nl/com.aspose.slides/layoutslideheaderfootermanager/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Stelt een manager voor die het gedrag van de voettekst-plaatsaanduiding, datum-tijd-plaatsaanduiding en paginanummer-plaatsaanduidingen van de lay-out-dia en alle onderliggende plaatsaanduidingen beheert. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia’s. Afhankelijke dia’s gebruiken en zijn afhankelijk van de lay-out-dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Wijzigt de zichtbaarheid van de voettekst-plaatsaanduiding van de lay-out-dia en alle onderliggende voettekst-plaatsaanduidingen. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Wijzigt de zichtbaarheid van de paginanummer-plaatsaanduiding van de lay-out-dia en alle onderliggende paginanummer-plaatsaanduidingen. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Wijzigt de zichtbaarheid van de datum-tijd-plaatsaanduiding van de lay-out-dia en alle onderliggende datum-tijd-plaatsaanduidingen. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Stelt tekst in op de voettekst-plaatsaanduiding van de lay-out-dia en alle onderliggende voettekst-plaatsaanduidingen. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Stelt tekst in op de datum-tijd-plaatsaanduiding van de lay-out-dia en alle onderliggende datum-tijd-plaatsaanduidingen. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de voettekst-plaatsaanduiding van de lay-out-dia en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia’s. Afhankelijke dia’s gebruiken en zijn afhankelijk van de master-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de voettekst-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de paginanummer-plaatsaanduiding van de lay-out-dia en alle onderliggende paginanummer-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia’s. Afhankelijke dia’s gebruiken en zijn afhankelijk van de lay-out-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de paginanummer-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de datum-tijd-plaatsaanduiding van de lay-out-dia en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia’s. Afhankelijke dia’s gebruiken en zijn afhankelijk van de lay-out-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de datum-tijd-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Stelt tekst in op de voettekst-plaatsaanduiding van de lay-out-dia en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia’s. Afhankelijke dia’s gebruiken en zijn afhankelijk van de lay-out-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst om in te stellen. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Stelt tekst in op de datum-tijd-plaatsaanduiding van de lay-out-dia en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia’s. Afhankelijke dia’s gebruiken en zijn afhankelijk van de lay-out-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst om in te stellen. |