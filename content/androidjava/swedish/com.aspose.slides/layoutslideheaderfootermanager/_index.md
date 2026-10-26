---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en manager som hanterar beteendet för layoutbildens sidfot, datum-tid, sidnummer-platshållare och alla underordnade platshållare.
type: docs
url: /sv/com.aspose.slides/layoutslideheaderfootermanager/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Representerar en manager som håller beteendet för layout-bildens sidfot, datum-tid, sidnummer-platshållare och alla underordnade platshållare. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes layout slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes layout slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes layout slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to layout slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to layout slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändrar layout-bildens sidfot-platshållare och alla underordnade sidfot-platshållare synlighet. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av mastersliden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör sidfot-platshållare synliga, annars - döljer dem. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändrar layout-bildens sidnummer-platshållare och alla underordnade sidnummer-platshållare synlighet. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör sidnummer-platshållare synliga, annars - döljer dem. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändrar layout-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare synlighet. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör datum-tid-platshållare synliga, annars - döljer dem. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Sätter text till layout-bildens sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Sätter text till layout-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare betyder att platshållare finns på beroende bilder. Beroende bilder använder och är beroende av layout-bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |