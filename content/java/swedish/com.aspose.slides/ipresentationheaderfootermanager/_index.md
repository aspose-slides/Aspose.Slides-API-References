---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides för Java API-referens
description: Representerar en manager som innehåller beteendet för alla sidfot-, datum-tid- och sidnummer-platshållare i presentationen.
type: docs
url: /sv/com.aspose.slides/ipresentationheaderfootermanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Representerar en manager som innehåller beteendet för alla sidfot-, datum-tid- och sidnummer-platshållare i presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Ändrar synligheten för alla huvud-platshållare, inklusive notes master, notes slides och handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Ändrar synligheten för alla sidfot-platshållare, inklusive master slides, layout slides och slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Ändrar synligheten för alla sidnummer-platshållare, inklusive master slides, layout slides och slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Ändrar synligheten för alla datum-tid-platshållare, inkluderar master slides, layout slides och slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Ställer in text för alla huvud-platshållare, inklusive notes master, notes slides och handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Ställer in text för alla sidfot-platshållare, inklusive master slides, layout slides och slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Ställer in text för alla datum-tid-platshållare, inklusive master slides, layout slides och slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Ändrar synligheten för sidfot-, datum-tid- och sidnummer-platshållare för alla titelslides och för den första layout-sliden. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Ändrar synligheten för alla huvud-platshållare, inklusive notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör header-platshållare synliga, annars döljs de. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Ändrar synligheten för alla sidfot-platshållare, inklusive master slides, layout slides och slides.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör footer-platshållare synliga, annars döljs de. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Ändrar synligheten för alla sidnummer-platshållare, inklusive master slides, layout slides och slides.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör page number-platshållare synliga, annars döljs de. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Ändrar synligheten för alla datum-tid-platshållare, inklusive master slides, layout slides och slides.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör date-time-platshållare synliga, annars döljs de. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Ställer in text för alla huvud-platshållare, inklusive notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Ställer in text för alla sidfot-platshållare, inklusive master slides, layout slides och slides.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Ställer in text för alla datum-tid-platshållare, inklusive master slides, layout slides och slides.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Ändrar synligheten för sidfot-, datum-tid- och sidnummer-platshållare för alla titelslides och för den första layout-sliden. Title slides \\u2013 slides baserade på den första layout-sliden (oavsett typ av denna första layout).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör platshållare synliga, annars döljs de. |