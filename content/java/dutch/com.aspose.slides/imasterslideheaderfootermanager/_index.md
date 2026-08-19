---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een manager voor die het gedrag van de voettekst-, datum-tijd- en paginanummer-placeholders van de masterdia en alle onderliggende placeholders beheert.
type: docs
url: /nl/com.aspose.slides/imasterslideheaderfootermanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Stelt een manager voor die het gedrag van de voettekstplaceholder van de masterdia, datum-tijd-placeholder, paginanummer-placeholder en alle onderliggende placeholders beheert. Onderliggende placeholders betekenen dat placeholders zich bevinden op afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de masterdia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Wijzigt de zichtbaarheid van de voettekstplaceholder van de masterdia en alle onderliggende voettekst-placeholders. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Wijzigt de zichtbaarheid van de paginanummer-placeholder van de masterdia en alle onderliggende paginanummer-placeholders. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Wijzigt de zichtbaarheid van de datum-tijd-placeholder van de masterdia en alle onderliggende datum-tijd-placeholders. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Stelt tekst in voor de voettekstplaceholder van de masterdia en alle onderliggende voettekst-placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Stelt tekst in voor de datum-tijd-placeholder van de masterdia en alle onderliggende datum-tijd-placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Wijzigt de zichtbaarheid van de voettekstplaceholder van de masterdia en alle onderliggende voettekst-placeholders. Onderliggende placeholders betekenen dat placeholders zich bevinden op afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de masterdia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true – maakt voettekst-placeholders zichtbaar, anders worden ze verborgen. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Wijzigt de zichtbaarheid van de paginanummer-placeholder van de masterdia en alle onderliggende paginanummer-placeholders. Onderliggende placeholders betekenen dat placeholders zich bevinden op afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de masterdia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true – maakt paginanummer-placeholders zichtbaar, anders worden ze verborgen. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Wijzigt de zichtbaarheid van de datum-tijd-placeholder van de masterdia en alle onderliggende datum-tijd-placeholders. Onderliggende placeholders betekenen dat placeholders zich bevinden op afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de masterdia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true – maakt datum-tijd-placeholders zichtbaar, anders worden ze verborgen. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Stelt tekst in voor de voettekstplaceholder van de masterdia en alle onderliggende voettekst-placeholders. Onderliggende placeholders betekenen dat placeholders zich bevinden op afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de masterdia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | In te stellen tekst. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Stelt tekst in voor de datum-tijd-placeholder van de masterdia en alle onderliggende datum-tijd-placeholders. Onderliggende placeholders betekenen dat placeholders zich bevinden op afhankelijke lay-outdia's en afhankelijke dia's. Afhankelijke lay-outdia's en dia's gebruiken en zijn afhankelijk van de masterdia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | In te stellen tekst. |