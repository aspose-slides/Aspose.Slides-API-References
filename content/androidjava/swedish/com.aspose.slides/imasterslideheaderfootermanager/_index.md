---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en manager som hanterar beteendet för masterbildens sidfot, datum-tid, sidnummer-platshållare och alla underordnade platshållare.
type: docs
url: /sv/com.aspose.slides/imasterslideheaderfootermanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representerar en manager som hanterar beteendet för masterbildens sidfot, datum-tid, sidnummer-platshållare och alla underordnade platshållare. Underordnade platshållare innebär att platshållare finns på beroende layoutbilder och beroende bilder. Beroende layoutbilder och bilder använder och är beroende av masterbilden.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändrar synligheten för masterbildens sidfot-platshållare och alla underordnade sidfot-platshållare. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändrar synligheten för masterbildens sidnummer-platshållare och alla underordnade sidnummer-platshållare. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändrar synligheten för masterbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sätter text till masterbildens sidfot-platshållare och alla underordnade sidfot-platshållare. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sätter text till masterbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Ändrar synligheten för masterbildens sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare innebär att platshållare finns på beroende layoutbilder och beroende bilder. Beroende layoutbilder och bilder använder och är beroende av masterbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör sidfot-platshållare synliga, annars – döljer dem. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Ändrar synligheten för masterbildens sidnummer-platshållare och alla underordnade sidnummer-platshållare. Underordnade platshållare innebär att platshållare finns på beroende layoutbilder och beroende bilder. Beroende layoutbilder och bilder använder och är beroende av masterbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör sidnummer-platshållare synliga, annars – döljer dem. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Ändrar synligheten för masterbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare innebär att platshållare finns på beroende layoutbilder och beroende bilder. Beroende layoutbilder och bilder använder och är beroende av masterbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör datum-tid-platshållare synliga, annars – döljer dem. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Sätter text till masterbildens sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare innebär att platshållare finns på beroende layoutbilder och beroende bilder. Beroende layoutbilder och bilder använder och är beroende av masterbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Sätter text till masterbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare innebär att platshållare finns på beroende layoutbilder och beroende bilder. Beroende layoutbilder och bilder använder och är beroende av masterbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |