---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Manager dar, der das Verhalten der Fußzeilen-Platzhalter, Datums-Uhrzeit-Platzhalter und Seitenzahlen-Platzhalter des Layout-Slides sowie aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/layoutslideheaderfootermanager/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters, des Datums-Uhrzeit-Platzhalters und des Seitenzahl-Platzhalters des Layout-Slides sowie aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters des Layout-Slides und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Master-Slide ab. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Seitenzahl-Platzhalters des Layout-Slides und aller untergeordneten Seitenzahl-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datums-Uhrzeit-Platzhalters des Layout-Slides und aller untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt Text für den Fußzeilen-Platzhalter des Layout-Slides und alle untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt Text für den Datums-Uhrzeit-Platzhalter des Layout-Slides und alle untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Fußzeilen-Platzhalters des Layout-Slides und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Master-Slide ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Fußzeilen-Platzhalter sichtbar, sonst - blendet sie aus. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Seitenzahl-Platzhalters des Layout-Slides und aller untergeordneten Seitenzahl-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Seitenzahl-Platzhalter sichtbar, sonst - blendet sie aus. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Datums-Uhrzeit-Platzhalters des Layout-Slides und aller untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Datums-Uhrzeit-Platzhalter sichtbar, sonst - blendet sie aus. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Setzt Text für den Fußzeilen-Platzhalter des Layout-Slides und alle untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text, der gesetzt werden soll. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Setzt Text für den Datums-Uhrzeit-Platzhalter des Layout-Slides und alle untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Slide ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text, der gesetzt werden soll. |