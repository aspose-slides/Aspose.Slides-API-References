---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Manager dar, der das Verhalten der Master-Folienfußzeile, des Datums-Uhrzeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/imasterslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten des Master-Folienfußzeilen-Platzhalters, des Datums-Uhrzeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen vom Master-Folienlayout ab.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Änderungen der Sichtbarkeit des Master-Folienfußzeilen-Platzhalters und aller untergeordneten Fußzeilen-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Änderungen der Sichtbarkeit des Master-Folienseitenzahlen-Platzhalters und aller untergeordneten Seitenzahlen-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Änderungen der Sichtbarkeit des Master-Foliendatums-Uhrzeit-Platzhalters und aller untergeordneten Datums-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt Text für den Master-Folienfußzeilen-Platzhalter und alle untergeordneten Fußzeilen-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt Text für den Master-Foliendatums-Uhrzeit-Platzhalter und alle untergeordneten Datums-Uhrzeit-Platzhalter. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Master-Folienfußzeilen-Platzhalters und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen vom Master-Folienlayout ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Fußzeilen-Platzhalter sichtbar, andernfalls - versteckt sie. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Master-Folienseitenzahlen-Platzhalters und aller untergeordneten Seitenzahlen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen vom Master-Folienlayout ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Seitenzahlen-Platzhalter sichtbar, andernfalls - versteckt sie. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Master-Foliendatums-Uhrzeit-Platzhalters und aller untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen vom Master-Folienlayout ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Datums-Uhrzeit-Platzhalter sichtbar, andernfalls - versteckt sie. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Setzt Text für den Master-Folienfußzeilen-Platzhalter und alle untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen vom Master-Folienlayout ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text, der gesetzt werden soll. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Setzt Text für den Master-Foliendatums-Uhrzeit-Platzhalter und alle untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen vom Master-Folienlayout ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text, der gesetzt werden soll. |