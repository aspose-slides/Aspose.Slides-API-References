---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en manager som håller beteendet för layout-bildens sidfot-, datum-tid- och sidnummer-platshållare samt alla underordnade platshållare.
type: docs
url: /sv/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representerar en manager som hanterar beteendet för layout-bildens sidfot-, datum-tid- och sidnummer-platshållare samt alla underordnade platshållare. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändrar layout-bildens sidfot-platshållare och alla underordnade sidfot-platshållares synlighet. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändrar layout-bildens sidnummer-platshållare och alla underordnade sidnummer-platshållares synlighet. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändrar layout-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållares synlighet. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ställer in text för layout-bildens sidfot-platshållare och alla underordnade sidfot-platshållare. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ställer in text för layout-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändrar layout-bildens sidfot-platshållare och alla underordnade sidfot-platshållares synlighet. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av master-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör sidfot-platshållare synliga, annars – döljer dem. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändrar layout-bildens sidnummer-platshållare och alla underordnade sidnummer-platshållares synlighet. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör sidnummer-platshållare synliga, annars – döljer dem. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändrar layout-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållares synlighet. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör datum-tid-platshållare synliga, annars – döljer dem. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ställer in text för layout-bildens sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ställer in text för layout-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |