---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een manager voor die het gedrag van de layout-slide-footer, datum-tijd- en paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen beheert.
type: docs
url: /nl/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Stelt een manager voor die het gedrag van de layout-slide-footer, datum-tijd- en paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen beheert. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich op afhankelijke dia’s bevinden. Afhankelijke dia’s gebruiken en zijn afhankelijk van de layout-slide.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Wijzigt de zichtbaarheid van de layout-slide-footer-placeholder en alle onderliggende footer-placeholders. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Wijzigt de zichtbaarheid van de layout-slide-paginanummer-placeholder en alle onderliggende paginanummer-placeholders. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Wijzigt de zichtbaarheid van de layout-slide-datum-tijd-placeholder en alle onderliggende datum-tijd-placeholders. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Stelt tekst in voor de layout-slide-footer-placeholder en alle onderliggende footer-placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Stelt tekst in voor de layout-slide-datum-tijd-placeholder en alle onderliggende datum-tijd-placeholders. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de layout-slide-footer-placeholder en alle onderliggende footer-placeholders. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich op afhankelijke dia’s bevinden. Afhankelijke dia’s gebruiken en zijn afhankelijk van de master-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true – maakt footer-placeholders zichtbaar, anders – verbergt ze. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de layout-slide-paginanummer-placeholder en alle onderliggende paginanummer-placeholders. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich op afhankelijke dia’s bevinden. Afhankelijke dia’s gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true – maakt paginanummer-placeholders zichtbaar, anders – verbergt ze. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de layout-slide-datum-tijd-placeholder en alle onderliggende datum-tijd-placeholders. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich op afhankelijke dia’s bevinden. Afhankelijke dia’s gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true – maakt datum-tijd-placeholders zichtbaar, anders – verbergt ze. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Stelt tekst in voor de layout-slide-footer-placeholder en alle onderliggende footer-placeholders. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich op afhankelijke dia’s bevinden. Afhankelijke dia’s gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | In te stellen tekst. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Stelt tekst in voor de layout-slide-datum-tijd-placeholder en alle onderliggende datum-tijd-placeholders. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich op afhankelijke dia’s bevinden. Afhankelijke dia’s gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | In te stellen tekst. |