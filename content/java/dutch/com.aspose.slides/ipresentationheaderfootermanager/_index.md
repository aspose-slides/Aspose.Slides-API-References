---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een manager die het gedrag van alle footer-, datum-tijd- en paginanummer-plaatsaanduidingen van de presentatie beheert.
type: docs
url: /nl/com.aspose.slides/ipresentationheaderfootermanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Representeert een manager die het gedrag van alle footer-, datum-tijd- en paginanummer-plaatsaanduidingen van een presentatie beheert.

## Methodes

| Methode | Beschrijving |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Verandert de zichtbaarheid van alle header-plaatsaanduidingen, inclusief notes-master, notes-dia's en handout-master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Verandert de zichtbaarheid van alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Verandert de zichtbaarheid van alle pagina-nummer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Verandert de zichtbaarheid van alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Stelt de tekst in voor alle header-plaatsaanduidingen, inclusief notes-master, notes-dia's en handout-master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Stelt de tekst in voor alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Stelt de tekst in voor alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Verandert de zichtbaarheid van de footer-, datum-tijd- en pagina-nummer-plaatsaanduidingen voor alle titel-dia's en voor de eerste lay-out-dia. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Verandert de zichtbaarheid van alle header-plaatsaanduidingen, inclusief notes-master, notes-dia's en handout-master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de header-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Verandert de zichtbaarheid van alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de footer-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Verandert de zichtbaarheid van alle pagina-nummer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de pagina-nummer-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Verandert de zichtbaarheid van alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de datum-tijd-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Stelt de tekst in voor alle header-plaatsaanduidingen, inclusief notes-master, notes-dia's en handout-master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Stelt de tekst in voor alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Stelt de tekst in voor alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Verandert de zichtbaarheid van de footer-, datum-tijd- en pagina-nummer-plaatsaanduidingen voor alle titel-dia's en voor de eerste lay-out-dia. Titel-dia's – dia's gebaseerd op de eerste lay-out-dia (ongeacht het type van deze eerste lay-out).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de plaatsaanduidingen zichtbaar, anders - verbergt ze. |