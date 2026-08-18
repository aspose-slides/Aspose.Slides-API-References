---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Manager dar, der das Verhalten der Footer-Datum-Uhrzeit- und Seitenzahl-Platzhalter für alle Folientypen verwaltet.
type: docs
url: /de/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Stellt einen Manager dar, der das Verhalten der Footer-, Datum-Uhrzeit- und Seitenzahl-Platzhalter für alle Folientypen verwaltet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Gibt an, ob ein Footer-Platzhalter vorhanden ist. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Gibt an, ob ein Seitenzahl-Platzhalter vorhanden ist. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Gibt an, ob ein Datum-Uhrzeit-Platzhalter vorhanden ist. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Ändert die Sichtbarkeit des Folien-Footer-Platzhalters. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Ändert die Sichtbarkeit des Folien-Seitenzahl-Platzhalters. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Ändert die Sichtbarkeit des Folien-Datum-Uhrzeit-Platzhalters. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Setzt den Text für den Folien-Footer-Platzhalter. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Setzt den Text für den Folien-Datum-Uhrzeit-Platzhalter. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Gibt an, ob ein Footer-Platzhalter vorhanden ist. Lese booleschen Wert.

**Rückgabe:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Gibt an, ob ein Seitenzahl-Platzhalter vorhanden ist. Lese booleschen Wert.

**Rückgabe:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Gibt an, ob ein Datum-Uhrzeit-Platzhalter vorhanden ist. Lese booleschen Wert.

**Rückgabe:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Folien-Footer-Platzhalters.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht einen Footer-Platzhalter sichtbar, andernfalls - blendet ihn aus. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Folien-Seitenzahl-Platzhalters.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht einen Seitenzahl-Platzhalter sichtbar, andernfalls - blendet ihn aus. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Folien-Datum-Uhrzeit-Platzhalters.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht einen Datum-Uhrzeit-Platzhalter sichtbar, andernfalls - blendet ihn aus. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Setzt den Text für den Folien-Footer-Platzhalter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Setzt den Text für den Folien-Datum-Uhrzeit-Platzhalter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |