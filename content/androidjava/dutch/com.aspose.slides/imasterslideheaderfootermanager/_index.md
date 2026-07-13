---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een manager die het gedrag van de voettekst-, datum-tijd- en paginanummer-plaatsaanduiders van de master-dia en alle onderliggende plaatsaanduiders bevat.
type: docs
url: /nl/com.aspose.slides/imasterslideheaderfootermanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Vertegenwoordigt een manager die het gedrag van de voettekst, datum-tijd en paginanummer-plaatsaanduiders van de master-dia en alle onderliggende plaatsaanduiders bevat. Onderliggende plaatsaanduiders betekenen dat de plaatsaanduiders zijn opgenomen in afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de master-dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Verandert de zichtbaarheid van de voettekst-plaatsaanduiding van de master-dia en alle onderliggende voettekst-plaatsaanduidingen. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Verandert de zichtbaarheid van de paginanummer-plaatsaanduiding van de master-dia en alle onderliggende paginanummer-plaatsaanduidingen. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Verandert de zichtbaarheid van de datum-tijd-plaatsaanduiding van de master-dia en alle onderliggende datum-tijd-plaatsaanduidingen. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Stelt tekst in voor de voettekst-plaatsaanduiding van de master-dia en alle onderliggende voettekst-plaatsaanduidingen. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Stelt tekst in voor de datum-tijd-plaatsaanduiding van de master-dia en alle onderliggende datum-tijd-plaatsaanduidingen. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Verandert de zichtbaarheid van de voettekst-plaatsaanduiding van de master-dia en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduiders betekenen dat de plaatsaanduiders zijn opgenomen in afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de master-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de voettekst-plaatsaanduiders zichtbaar, anders worden ze verborgen. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Verandert de zichtbaarheid van de paginanummer-plaatsaanduiding van de master-dia en alle onderliggende paginanummer-plaatsaanduidingen. Onderliggende plaatsaanduiders betekenen dat de plaatsaanduiders zijn opgenomen in afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de master-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de paginanummer-plaatsaanduiders zichtbaar, anders worden ze verborgen. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Verandert de zichtbaarheid van de datum-tijd-plaatsaanduiding van de master-dia en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduiders betekenen dat de plaatsaanduiders zijn opgenomen in afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de master-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de datum-tijd-plaatsaanduiders zichtbaar, anders worden ze verborgen. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Stelt tekst in voor de voettekst-plaatsaanduiding van de master-dia en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduiders betekenen dat de plaatsaanduiders zijn opgenomen in afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de master-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Stelt tekst in voor de datum-tijd-plaatsaanduiding van de master-dia en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduiders betekenen dat de plaatsaanduiders zijn opgenomen in afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de master-dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |