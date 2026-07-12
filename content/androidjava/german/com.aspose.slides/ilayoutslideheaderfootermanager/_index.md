---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Manager dar, der das Verhalten von Fußzeilen-, Datum-Uhrzeit- und Foliennummern-Platzhaltern einer Layout-Folie sowie aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten von Fußzeilen-, Datum-Uhrzeit- und Foliennummern-Platzhaltern einer Layout-Folie sowie aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass die Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters einer Layout-Folie und aller untergeordneten Fußzeilen-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Foliennummer-Platzhalters einer Layout-Folie und aller untergeordneten Foliennummer-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters einer Layout-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt den Text für den Fußzeilen-Platzhalter einer Layout-Folie und aller untergeordneten Fußzeilen-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt den Text für den Datum-Uhrzeit-Platzhalter einer Layout-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Fußzeilen-Platzhalters einer Layout-Folie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass die Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Master-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Fußzeilen-Platzhalter sichtbar, sonst werden sie ausgeblendet. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Foliennummer-Platzhalters einer Layout-Folie und aller untergeordneten Foliennummer-Platzhalter. Untergeordnete Platzhalter bedeuten, dass die Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Foliennummer-Platzhalter sichtbar, sonst werden sie ausgeblendet. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters einer Layout-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass die Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datum-Uhrzeit-Platzhalter sichtbar, sonst werden sie ausgeblendet. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Setzt den Text für den Fußzeilen-Platzhalter einer Layout-Folie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass die Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Setzt den Text für den Datum-Uhrzeit-Platzhalter einer Layout-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass die Platzhalter auf abhängigen Folien enthalten sind. Abhängige Folien verwenden und hängen von der Layout-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |