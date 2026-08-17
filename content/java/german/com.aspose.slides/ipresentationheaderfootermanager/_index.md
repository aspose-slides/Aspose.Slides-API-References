---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Manager dar, der das Verhalten aller Footer-, Datums- und Seitenzahlen-Platzhalter der Präsentation enthält.
type: docs
url: /de/com.aspose.slides/ipresentationheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten aller Footer-, Datums- und Seitenzahlen-Platzhalter der Präsentation enthält.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Ändert die Sichtbarkeit aller Header-Platzhalter, einschließlich Notiz-Master, Notiz-Folien und Handzettel-Master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Ändert die Sichtbarkeit aller Footer-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit aller Seitenzahlen-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit aller Datums- und Zeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Setzt den Text für alle Header-Platzhalter, einschließlich Notiz-Master, Notiz-Folien und Handzettel-Master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Setzt den Text für alle Footer-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Setzt den Text für alle Datums- und Zeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Ändert die Sichtbarkeit der Footer-, Datums- und Zeit- sowie Seitenzahlen-Platzhalter für alle Titelfolien und für die erste Layout-Folie. Titelfolien – Folien, die auf der ersten Layout-Folie basieren (unabhängig vom Typ dieses ersten Layouts). |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Header-Platzhalter, einschließlich Notiz-Master, Notiz-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Header-Platzhalter sichtbar, andernfalls – blendet sie aus. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Footer-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Footer-Platzhalter sichtbar, andernfalls – blendet sie aus. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Seitenzahlen-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Seitenzahlen-Platzhalter sichtbar, andernfalls – blendet sie aus. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit aller Datums- und Zeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Datums- und Zeit-Platzhalter sichtbar, andernfalls – blendet sie aus. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Setzt den Text für alle Header-Platzhalter, einschließlich Notiz-Master, Notiz-Folien und Handzettel-Master.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Setzt den Text für alle Footer-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Setzt den Text für alle Datums- und Zeit-Platzhalter, einschließlich Master-Folien, Layout-Folien und Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Ändert die Sichtbarkeit der Footer-, Datums- und Zeit- sowie Seitenzahlen-Platzhalter für alle Titelfolien und für die erste Layout-Folie. Titelfolien – Folien, die auf der ersten Layout-Folie basieren (unabhängig vom Typ dieses ersten Layouts).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht die Platzhalter sichtbar, andernfalls – blendet sie aus. |