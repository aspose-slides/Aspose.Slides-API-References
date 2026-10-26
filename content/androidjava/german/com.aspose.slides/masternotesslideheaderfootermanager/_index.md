---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt einen Manager dar, der das Verhalten der Fußzeilen-, Datum-Uhrzeit- und Seitenzahlen-Platzhalter der Master-Notizfolie sowie aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/masternotesslideheaderfootermanager/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters der Master-Notizfolie, des Datum-Uhrzeit-Platzhalters und des Seitenzahlen-Platzhalters sowie aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Ändert die Sichtbarkeit des Header-Platzhalters der Master-Notizfolie und aller untergeordneten Header-Platzhalter. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Setzt den Text für den Header-Platzhalter der Master-Notizfolie und aller untergeordneten Header-Platzhalter. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Master-Folie und aller untergeordneten Fußzeilen-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Seitenzahlen-Platzhalters der Master-Folie und aller untergeordneten Seitenzahlen-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Master-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt den Text für den Fußzeilen-Platzhalter der Master-Folie und aller untergeordneten Fußzeilen-Platzhalter. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt den Text für den Datum-Uhrzeit-Platzhalter der Master-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Header-Platzhalters der Master-Notizfolie und aller untergeordneten Header-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Header-Platzhalter sichtbar, sonst - blendet sie aus. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

Setzt den Text für den Header-Platzhalter der Master-Notizfolie und aller untergeordneten Header-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Master-Folie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Fußzeilen-Platzhalter sichtbar, sonst - blendet sie aus. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Seitenzahlen-Platzhalters der Master-Folie und aller untergeordneten Seitenzahlen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Seitenzahlen-Platzhalter sichtbar, sonst - blendet sie aus. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Master-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht die Datum-Uhrzeit-Platzhalter sichtbar, sonst - blendet sie aus. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Setzt den Text für den Fußzeilen-Platzhalter der Master-Folie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Setzt den Text für den Datum-Uhrzeit-Platzhalter der Master-Folie und aller untergeordneten Datum-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |