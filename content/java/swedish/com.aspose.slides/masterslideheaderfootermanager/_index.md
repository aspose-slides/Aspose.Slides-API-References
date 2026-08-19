---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides för Java API-referens
description: Representerar en manager som hanterar beteendet för master-bildens sidfot-, datum-tid- och sidnummer-platshållare samt alla underordnade platshållare.
type: docs
url: /sv/com.aspose.slides/masterslideheaderfootermanager/
---
**Arv:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Alla implementerade gränssnitt:**  
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)  
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Representerar en manager som hanterar beteendet för master-bildens sidfot, datum-tid, sidnummer-platshållare och alla underordnade platshållare. Underordnade platshållare betyder att platshållare finns på beroende layout-bilder och beroende bilder. Beroende layout-bilder och bilder använder och beror på master-bilden.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändrar synligheten för master-bildens sidfot-platshållare och alla underordnade sidfot-platshållare. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändrar synligheten för master-bildens sidnummer-platshållare och alla underordnade sidnummer-platshållare. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändrar synligheten för master-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ställer in text för master-bildens sidfot-platshållare och alla underordnade sidfot-platshållare. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ställer in text för master-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändrar synligheten för master-bildens sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare betyder att platshållare finns på beroende layout-bilder och beroende bilder. Beroende layout-bilder och bilder använder och beror på master-bilden.

**Parametrar:**  
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör en sidfot-platshållare synlig, annars – döljer den. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändrar synligheten för master-bildens sidnummer-platshållare och alla underordnade sidnummer-platshållare. Underordnade platshållare betyder att platshållare finns på beroende layout-bilder och beroende bilder. Beroende layout-bilder och bilder använder och beror på master-bilden.

**Parametrar:**  
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör en sidnummer-platshållare synlig, annars – döljer den. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändrar synligheten för master-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare betyder att platshållare finns på beroende layout-bilder och beroende bilder. Beroende layout-bilder och bilder använder och beror på master-bilden.

**Parametrar:**  
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör en datum-tid-platshållare synlig, annars – döljer den. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ställer in text för master-bildens sidfot-platshållare och alla underordnade sidfot-platshållare. Underordnade platshållare betyder att platshållare finns på beroende layout-bilder och beroende bilder. Beroende layout-bilder och bilder använder och beror på master-bilden.

**Parametrar:**  
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ställer in text för master-bildens datum-tid-platshållare och alla underordnade datum-tid-platshållare. Underordnade platshållare betyder att platshållare finns på beroende layout-bilder och beroende bilder. Beroende layout-bilder och bilder använder och beror på master-bilden.

**Parametrar:**  
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |