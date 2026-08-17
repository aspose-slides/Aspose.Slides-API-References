---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Manager dar, der das Verhalten der Layout-Folienfußzeile, des Datums-Uhrzeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Stellt den Manager dar, der das Verhalten des Layout-Folienfußzeilen-Platzhalters, des Datums-Uhrzeit-Platzhalters und des Seitenzahlen-Platzhalters sowie aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Folien ab.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Layout-Folienfußzeilen-Platzhalters und aller untergeordneten Fußzeilen-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Layout-Folienseitenzahl-Platzhalters und aller untergeordneten Seitenzahlen-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Layout-Foliendatums-Uhrzeit-Platzhalters und aller untergeordneten Datums-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt den Text für den Layout-Folienfußzeilen-Platzhalter und alle untergeordneten Fußzeilen-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt den Text für den Layout-Foliendatums-Uhrzeit-Platzhalter und alle untergeordneten Datums-Uhrzeit-Platzhalter. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Layout-Folienfußzeilen-Platzhalters und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Master-Folien ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Fußzeilen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Layout-Folienseitenzahl-Platzhalters und aller untergeordneten Seitenzahlen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Folien ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Seitenzahlen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Layout-Foliendatums-Uhrzeit-Platzhalters und aller untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Folien ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datums-Uhrzeit-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Setzt den Text für den Layout-Folienfußzeilen-Platzhalter und alle untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Folien ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Setzt den Text für den Layout-Foliendatums-Uhrzeit-Platzhalter und alle untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen vom Layout-Folien ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |