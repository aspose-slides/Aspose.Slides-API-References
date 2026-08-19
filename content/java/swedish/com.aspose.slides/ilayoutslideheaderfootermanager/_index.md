---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides för Java API-referens
description: Representerar en manager som hanterar beteendet för layoutbildens sidfot, datum-tid- och sidnummer-platshållare samt alla underordnade platshållare.
type: docs
url: /sv/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representerar en manager som hanterar beteendet för layoutbildens sidfot, datum-tid-platshållare och sidnummer-platshållare samt alla underordnade platshållare. Underordnade platshållare innebär att platshållarna finns på beroende bilder. Beroende bilder använder och är beroende av layoutbilden.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändrar layoutbildens sidfot-platshållare och alla underordnade sidfot-platshållare synlighet. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändrar layoutbildens sidnummer-platshållare och alla underordnade sidnummer-platshållare synlighet. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändrar layoutbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare synlighet. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ställer in text för layoutbildens sidfot-platshållare och alla underordnade sidfot-platshållare. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ställer in text för layoutbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändrar layoutbildens sidfot-platshållare och alla underordnade sidfot-platshållare synlighet. Underordnade platshållare innebär att platshållarna finns på beroende bilder. Beroende bilder använder och är beroende av master-bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör sidfot-platshållare synlig, annars - döljer dem. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändrar layoutbildens sidnummer-platshållare och alla underordnade sidnummer-platshållare synlighet. Underordnade platshållare innebär att platshållarna finns på beroende bilder. Beroende bilder använder och är beroende av layoutbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör sidnummer-platshållare synlig, annars - döljer dem. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändrar layoutbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare synlighet. Underordnade platshållare innebär att platshållarna finns på beroende bilder. Beroende bilder använder och är beroende av layoutbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör datum-tid-platshållare synlig, annars - döljer dem. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ställer in text för layoutbildens sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare innebär att platshållarna finns på beroende bilder. Beroende bilder använder och är beroende av layoutbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ställer in text för layoutbildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare innebär att platshållarna finns på beroende bilder. Beroende bilder använder och är beroende av layoutbilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |