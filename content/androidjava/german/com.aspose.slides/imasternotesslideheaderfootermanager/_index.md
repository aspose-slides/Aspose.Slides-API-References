---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt den Manager dar, der das Verhalten der Fußzeilen-, Datum-Uhrzeit- und Seitenzahl-Platzhalter der Master-Notizfolie sowie aller Kind-Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Stellt den Manager dar, der das Verhalten des Fußzeilen-Platzhalters der Master-Notizfolie, des Datum-Uhrzeit-Platzhalters, des Seitenzahl-Platzhalters und aller Kind-Platzhalter verwaltet. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Ändert die Sichtbarkeit des Header-Platzhalters der Master-Notizfolie und aller Kind-Header-Platzhalter. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Setzt den Text für den Header-Platzhalter der Master-Notizfolie und aller Kind-Header-Platzhalter. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Footer-Platzhalters der Master-Notizfolie und aller Kind-Footer-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Master-Notizfolie und aller Kind-Seitenzahl-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Master-Notizfolie und aller Kind-Datum-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt den Text für den Footer-Platzhalter der Master-Notizfolie und aller Kind-Footer-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt den Text für den Datum-Uhrzeit-Platzhalter der Master-Notizfolie und aller Kind-Datum-Uhrzeit-Platzhalter. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Header-Platzhalters der Master-Notizfolie und aller Kind-Header-Platzhalter. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Header-Platzhalter sichtbar, andernfalls - blendet sie aus. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Setzt den Text für den Header-Platzhalter der Master-Notizfolie und aller Kind-Header-Platzhalter. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Footer-Platzhalters der Master-Notizfolie und aller Kind-Footer-Platzhalter. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Footer-Platzhalter sichtbar, andernfalls - blendet sie aus. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Master-Notizfolie und aller Kind-Seitenzahl-Platzhalter. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Seitenzahl-Platzhalter sichtbar, andernfalls - blendet sie aus. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Master-Notizfolie und aller Kind-Datum-Uhrzeit-Platzhalter. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Datum-Uhrzeit-Platzhalter sichtbar, andernfalls - blendet sie aus. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Setzt den Text für den Footer-Platzhalter der Master-Notizfolie und aller Kind-Footer-Platzhalter. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Setzt den Text für den Datum-Uhrzeit-Platzhalter der Master-Notizfolie und aller Kind-Datum-Uhrzeit-Platzhalter. Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |