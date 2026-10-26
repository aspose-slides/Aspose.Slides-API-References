---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en manager som hanterar beteendet för alla sidfot-, datum-tid- och sidnumrerings-platshållare i presentationen.
type: docs
url: /sv/com.aspose.slides/ipresentationheaderfootermanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Representerar en manager som hanterar beteendet för alla sidfot-, datum-tid- och sidnumrerings-platshållare i presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Ändrar synligheten för alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Ändrar synligheten för alla sidfotplatshållare, inklusive master-bilder, layout-bilder och bilder. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Ändrar synligheten för alla sidnumreringsplatshållare, inklusive master-bilder, layout-bilder och bilder. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Ändrar synligheten för alla datum-tid-platshållare, inklusive master-bilder, layout-bilder och bilder. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Ställer in text för alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Ställer in text för alla sidfotplatshållare, inklusive master-bilder, layout-bilder och bilder. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Ställer in text för alla datum-tid-platshållare, inklusive master-bilder, layout-bilder och bilder. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Ändrar synligheten för sidfot-, datum-tid- och sidnumrerings-platshållare för alla titelslides och för den första layout-sliden. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Ändrar synligheten för alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör rubrikplatshållare synliga, annars - döljer dem. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Ändrar synligheten för alla sidfotplatshållare, inklusive master-bilder, layout-bilder och bilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör sidfotplatshållare synliga, annars - döljer dem. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Ändrar synligheten för alla sidnumreringsplatshållare, inklusive master-bilder, layout-bilder och bilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör sidnumreringsplatshållare synliga, annars - döljer dem. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Ändrar synligheten för alla datum-tid-platshållare, inklusive master-bilder, layout-bilder och bilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör datum-tid-platshållare synliga, annars - döljer dem. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Ställer in text för alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Ställer in text för alla sidfotplatshållare, inklusive master-bilder, layout-bilder och bilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Ställer in text för alla datum-tid-platshållare, inklusive master-bilder, layout-bilder och bilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att ange. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Ändrar synligheten för sidfot-, datum-tid- och sidnumrerings-platshållare för alla titelslides och för den första layout-sliden. Titelslides — slides baserade på den första layout-sliden (oavsett typen av denna första layout).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör platshållarna synliga, annars - döljer dem. |