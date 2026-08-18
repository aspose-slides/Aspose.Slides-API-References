---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides für die Java-API-Referenz
description: Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters, des Datum-Uhrzeit-Platzhalters, des Seitenzahl-Platzhalters der Master-Notizfolie und aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters, des Datum-Uhrzeit-Platzhalters, des Seitenzahl-Platzhalters und aller untergeordneten Platzhalter der Master-Notizfolie verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Ändert die Sichtbarkeit des Header-Platzhalters der Master-Notizfolie und aller untergeordneten Header-Platzhalter. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Setzt den Text für den Header-Platzhalter der Master-Notizfolie und alle untergeordneten Header-Platzhalter. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Footer-Platzhalters der Master-Notizfolie und aller untergeordneten Footer-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Master-Notizfolie und aller untergeordneten Seitenzahl-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Master-Notizfolie und aller untergeordneten Datum-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt den Text für den Footer-Platzhalter der Master-Notizfolie und alle untergeordneten Footer-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt den Text für den Datum-Uhrzeit-Platzhalter der Master-Notizfolie und alle untergeordneten Datum-Uhrzeit-Platzhalter. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Header-Platzhalters der Master-Notizfolie und aller untergeordneten Header-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Header-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Setzt den Text für den Header-Platzhalter der Master-Notizfolie und alle untergeordneten Header-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Footer-Platzhalters der Master-Notizfolie und aller untergeordneten Footer-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Footer-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Master-Notizfolie und aller untergeordneten Seitenzahl-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Seitenzahl-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Master-Notizfolie und aller untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datum-Uhrzeit-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Setzt den Text für den Footer-Platzhalter der Master-Notizfolie und alle untergeordneten Footer-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Setzt den Text für den Datum-Uhrzeit-Platzhalter der Master-Notizfolie und alle untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |