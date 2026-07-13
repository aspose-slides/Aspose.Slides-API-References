---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een manager voor die het gedrag van alle footer, datum-tijd en paginanummer-plaatsaanduidingen van de presentatie bevat.
type: docs
url: /nl/com.aspose.slides/ipresentationheaderfootermanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Stelt een manager voor die het gedrag van alle footer, datum-tijd en paginanummer-plaatsaanduidingen van de presentatie bevat.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Wijzigt de zichtbaarheid van alle header-plaatsaanduidingen, inclusief notitie-master, notitie-dia's en hand-out-master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Wijzigt de zichtbaarheid van alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Wijzigt de zichtbaarheid van alle paginanummer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Wijzigt de zichtbaarheid van alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Stelt tekst in voor alle header-plaatsaanduidingen, inclusief notitie-master, notitie-dia's en hand-out-master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Stelt tekst in voor alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Stelt tekst in voor alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Wijzigt de zichtbaarheid van de footer-, datum-tijd- en paginanummer-plaatsaanduidingen voor alle titel-dia's en voor de eerste lay-out-dia. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van alle header-plaatsaanduidingen, inclusief notitie-master, notitie-dia's en hand-out-master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de header-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de footer-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van alle paginanummer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de paginanummer-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Wijzigt de zichtbaarheid van alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de datum-tijd-plaatsaanduidingen zichtbaar, anders - verbergt ze. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Stelt tekst in voor alle header-plaatsaanduidingen, inclusief notitie-master, notitie-dia's en hand-out-master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Stelt tekst in voor alle footer-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Stelt tekst in voor alle datum-tijd-plaatsaanduidingen, inclusief master-dia's, lay-out-dia's en dia's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden ingesteld. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Wijzigt de zichtbaarheid van de footer-, datum-tijd- en paginanummer-plaatsaanduidingen voor alle titel-dia's en voor de eerste lay-out-dia. Titel-dia's - dia's die gebaseerd zijn op de eerste lay-out-dia (onafhankelijk van het type van deze eerste lay-out).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | true - maakt de plaatsaanduidingen zichtbaar, anders - verbergt ze. |