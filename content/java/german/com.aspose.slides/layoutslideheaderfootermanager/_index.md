---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Manager dar, der das Verhalten der Fußzeilen-, Datum-Uhrzeit- und Folienzahl-Platzhalter der Layout-Folie sowie aller untergeordneten Platzhalter verwaltet.
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

Stellt einen Manager dar, der das Verhalten der Layout-Folie-Fußzeilen-, Datum-Uhrzeit- und Folienzahl-Platzhalter sowie aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Layout-Folie und aller untergeordneten Fußzeilen-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Folienzahl-Platzhalters der Layout-Folie und aller untergeordneten Folienzahl-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Layout-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt Text für den Fußzeilen-Platzhalter der Layout-Folie und alle untergeordneten Fußzeilen-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt Text für den Datum-Uhrzeit-Platzhalter der Layout-Folie und alle untergeordneten Datum-Uhrzeit-Platzhalter. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Layout-Folie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Master-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Fußzeilen-Platzhalter sichtbar, andernfalls – verbirgt sie. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Folienzahl-Platzhalters der Layout-Folie und aller untergeordneten Folienzahl-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Folienzahl-Platzhalter sichtbar, andernfalls – verbirgt sie. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Layout-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datum-Uhrzeit-Platzhalter sichtbar, andernfalls – verbirgt sie. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Setzt Text für den Fußzeilen-Platzhalter der Layout-Folie und alle untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Setzt Text für den Datum-Uhrzeit-Platzhalter der Layout-Folie und alle untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |