---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Manager dar, der das Verhalten aller Fußzeilen-Datum-Uhrzeit- und Seitenzahl-Platzhalter einer Präsentation verwaltet.
type: docs
url: /de/com.aspose.slides/ipresentationheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten aller Fußzeilen-, Datum-Uhrzeit- und Seitenzahl-Platzhalter einer Präsentation verwaltet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Ändert die Sichtbarkeit aller Kopfzeilen-Platzhalter, einschließlich Notizen-Master, Notizen-Folien und Handzettel-Master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Ändert die Sichtbarkeit aller Fußzeilen-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit aller Seitenzahl-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit aller Datum-Uhrzeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Setzt den Text für alle Kopfzeilen-Platzhalter, einschließlich Notizen-Master, Notizen-Folien und Handzettel-Master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Setzt den Text für alle Fußzeilen-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Setzt den Text für alle Datum-Uhrzeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Ändert die Sichtbarkeit der Fußzeilen-, Datum-Uhrzeit- und Seitenzahl-Platzhalter für alle Titelfolien und für die erste Layout-Folie. Titelfolien \\u2013 Folien, die auf der ersten Layout-Folie basieren (unabhängig vom Typ dieses ersten Layouts). |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Kopfzeilen-Platzhalter, einschließlich Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Kopfzeilen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Fußzeilen-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Fußzeilen-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Seitenzahl-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Seitenzahl-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Datum-Uhrzeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datum-Uhrzeit-Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Setzt den Text für alle Kopfzeilen-Platzhalter, einschließlich Notizen-Master, Notizen-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Setzt den Text für alle Fußzeilen-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Setzt den Text für alle Datum-Uhrzeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Ändert die Sichtbarkeit der Fußzeilen-, Datum-Uhrzeit- und Seitenzahl-Platzhalter für alle Titelfolien und für die erste Layout-Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Platzhalter sichtbar, andernfalls werden sie ausgeblendet. |