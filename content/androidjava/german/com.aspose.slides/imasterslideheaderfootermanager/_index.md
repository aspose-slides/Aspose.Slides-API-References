---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides für Android über Java API Reference
description: Stellt einen Manager dar, der das Verhalten der Fußzeilen-, Datum-Uhrzeit- und Seitenzahlen-Platzhalter der Masterfolie sowie aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/imasterslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters der Masterfolie, des Datum-Uhrzeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Masterfolie ab.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Masterfolie und aller untergeordneten Fußzeilen-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Seitenzahlen-Platzhalters der Masterfolie und aller untergeordneten Seitenzahlen-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Masterfolie und aller untergeordneten Datum-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt Text für den Fußzeilen-Platzhalter der Masterfolie und alle untergeordneten Fußzeilen-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt Text für den Datum-Uhrzeit-Platzhalter der Masterfolie und alle untergeordneten Datum-Uhrzeit-Platzhalter. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Masterfolie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Masterfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Fußzeilen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Seitenzahlen-Platzhalters der Masterfolie und aller untergeordneten Seitenzahlen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Masterfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Seitenzahlen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Masterfolie und aller untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Masterfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datum-Uhrzeit-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Setzt Text für den Fußzeilen-Platzhalter der Masterfolie und alle untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Masterfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Setzt Text für den Datum-Uhrzeit-Platzhalter der Masterfolie und alle untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Masterfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |