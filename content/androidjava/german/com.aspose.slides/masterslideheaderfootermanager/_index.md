---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Manager dar, der das Verhalten der Fußzeilen-, Datums- und Uhrzeit- sowie Seitenzahl-Platzhalter der Master-Folien und aller untergeordneten Platzhalter verwaltet.
type: docs
url: /de/com.aspose.slides/masterslideheaderfootermanager/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters der Master-Folien, des Datums-Uhrzeit-Platzhalters, des Seitenzahl-Platzhalters und aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Master-Folien und aller untergeordneten Fußzeilen-Platzhalter. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Master-Folien und aller untergeordneten Seitenzahl-Platzhalter. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ändert die Sichtbarkeit des Datums-Uhrzeit-Platzhalters der Master-Folien und aller untergeordneten Datums-Uhrzeit-Platzhalter. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Setzt den Text im Fußzeilen-Platzhalter der Master-Folien und allen untergeordneten Fußzeilen-Platzhaltern. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Setzt den Text im Datums-Uhrzeit-Platzhalter der Master-Folien und allen untergeordneten Datums-Uhrzeit-Platzhaltern. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Master-Folien und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht Fußzeilen-Platzhalter sichtbar, sonst - blendet sie aus. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Master-Folien und aller untergeordneten Seitenzahl-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht Seitenzahl-Platzhalter sichtbar, sonst - blendet sie aus. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Datums-Uhrzeit-Platzhalters der Master-Folien und aller untergeordneten Datums-Uhrzeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht Datums-Uhrzeit-Platzhalter sichtbar, sonst - blendet sie aus. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Setzt den Text im Fußzeilen-Platzhalter der Master-Folien und allen untergeordneten Fußzeilen-Platzhaltern. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Setzt den Text im Datums-Uhrzeit-Platzhalter der Master-Folien und allen untergeordneten Datums-Uhrzeit-Platzhaltern. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |