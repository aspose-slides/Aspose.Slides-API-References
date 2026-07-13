---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een manager voor die het gedrag van de layout slide footer, datum-tijd- en paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen beheert.
type: docs
url: /nl/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Stelt een manager voor die het gedrag van de layout-slide-footer, datum-tijd- en paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen beheert. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke slides. Afhankelijke slides gebruiken en zijn afhankelijk van de layout-slide.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Wijzigt de zichtbaarheid van de layout-slide-footerplaatsaanduiding en alle onderliggende footerplaatsaanduidingen. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Wijzigt de zichtbaarheid van de layout-slide-paginanummerplaatsaanduiding en alle onderliggende paginanummerplaatsaanduidingen. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Wijzigt de zichtbaarheid van de layout-slide-datum-tijd-plaatsaanduiding en alle onderliggende datum-tijd-plaatsaanduidingen. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Stelt tekst in voor de layout-slide-footerplaatsaanduiding en alle onderliggende footerplaatsaanduidingen. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Stelt tekst in voor de layout-slide-datum-tijd-plaatsaanduiding en alle onderliggende datum-tijd-plaatsaanduidingen. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de layout-slide-footerplaatsaanduiding en alle onderliggende footerplaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke slides. Afhankelijke slides gebruiken en zijn afhankelijk van de master-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de footer-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de layout-slide-paginanummerplaatsaanduiding en alle onderliggende paginanummerplaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke slides. Afhankelijke slides gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de paginanummer-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van de layout-slide-datum-tijd-plaatsaanduiding en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke slides. Afhankelijke slides gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de datum-tijd-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Stelt tekst in voor de layout-slide-footerplaatsaanduiding en alle onderliggende footerplaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke slides. Afhankelijke slides gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Te zetten tekst. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Stelt tekst in voor de layout-slide-datum-tijd-plaatsaanduiding en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke slides. Afhankelijke slides gebruiken en zijn afhankelijk van de layout-slide.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Te zetten tekst. |