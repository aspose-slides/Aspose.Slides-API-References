---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en manager som håller beteendet för alla sidfot-, datum-tid- och sidnummer-platshållare i presentationen.
type: docs
url: /sv/com.aspose.slides/presentationheaderfootermanager/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

Representerar en manager som håller beteendet för alla sidfot, datum-tid och sidnummer-platshållare i presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Ändrar synligheten för alla rubrik-platshållare, inklusive notes master, notes slides och handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Ändrar synligheten för alla sidfot-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Ändrar synligheten för alla sidnummer-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Ändrar synligheten för alla datum-tid-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sätter text till alla rubrik-platshållare, inklusive notes master, notes slides och handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sätter text till alla sidfot-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sätter text till alla datum-tid-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Ändrar synligheten för sidfot-, datum-tid- och sidnummer-platshållare för alla titelslides och för den första layout-sliden. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

Ändrar synligheten för alla rubrik-platshållare, inklusive notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör rubrik-platshållare synliga, annars döljs de. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

Ändrar synligheten för alla sidfot-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör sidfot-platshållare synliga, annars döljs de. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

Ändrar synligheten för alla sidnummer-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör sidnummer-platshållare synliga, annars döljs de. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

Ändrar synligheten för alla datum-tid-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör datum-tid-platshållare synliga, annars döljs de. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

Sätter text till alla rubrik-platshållare, inklusive notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text som ska sättas. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

Sätter text till alla sidfot-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text som ska sättas. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

Sätter text till alla datum-tid-platshållare, inklusive master slides, layout slides, slides, notes master, notes slides och handout master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text som ska sättas. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Ändrar synligheten för sidfot-, datum-tid- och sidnummer-platshållare för alla titelslides och för den första layout-sliden. Titelslides – slides baserade på den första layout-sliden (oavsett typ av denna första layout).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true – gör platshållarna synliga, annars döljs de. |