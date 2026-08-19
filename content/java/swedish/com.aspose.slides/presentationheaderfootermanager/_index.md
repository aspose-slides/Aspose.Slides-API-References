---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides för Java API-referens
description: Representerar en manager som innehåller beteendet för alla fot-, datum-tid- och sidnummer-platshållare i presentationen.
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

Representerar en manager som innehåller beteendet för alla fot-, datum-tid- och sidnummer-platshållare i presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Ändrar synligheten för alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Ändrar synligheten för alla fot-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Ändrar synligheten för alla sidnummer-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Ändrar synligheten för alla datum-tid-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sätter text till alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sätter text till alla fotplatshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sätter text till alla datum-tid-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Ändrar synligheten för fot-, datum-tid- och sidnummer-platshållare på alla titelslides och för den första layout-sliden. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

Ändrar synligheten för alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör rubrikplatshållarna synliga, annars - döljer dem. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

Ändrar synligheten för alla fot-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör fotplatshållarna synliga, annars - döljer dem. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

Ändrar synligheten för alla sidnummer-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör sidnummerplatshållarna synliga, annars - döljer dem. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

Ändrar synligheten för alla datum-tid-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör datum-tid-platshållarna synliga, annars - döljer dem. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

Sätter text till alla rubrikplatshållare, inklusive notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

Sätter text till alla fotplatshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

Sätter text till alla datum-tid-platshållare, inklusive master-bilder, layout-bilder, bilder, notes-master, notes-bilder och handout-master.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att sätta. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Ändrar synligheten för fot-, datum-tid- och sidnummer-platshållare på alla titelslides och för den första layout-sliden. Titelslides – slides baserade på den första layout-sliden (oavsett typ av den första layouten).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | true - gör platshållarna synliga, annars - döljer dem. |