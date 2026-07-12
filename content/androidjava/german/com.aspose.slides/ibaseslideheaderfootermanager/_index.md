---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt den Manager dar, der das Verhalten der Fußzeilen-Datum-Uhrzeit-Seitenzahl-Platzhalter für alle Folientypen verwaltet.
type: docs
url: /de/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Stellt den Manager dar, der das Verhalten der Fußzeilen-Platzhalter, Datum-Uhrzeit-Platzhalter und Seitenzahl-Platzhalter für alle Folientypen verwaltet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Liest den Wert, der anzeigt, dass ein Fußzeilen-Platzhalter vorhanden ist. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Liest den Wert, der anzeigt, dass ein Seitenzahl-Platzhalter vorhanden ist. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Liest den Wert, der anzeigt, dass ein Datum-Uhrzeit-Platzhalter vorhanden ist. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters auf der Folie. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Ändert die Sichtbarkeit des Seitenzahl-Platzhalters auf der Folie. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters auf der Folie. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Setzt den Text für den Fußzeilen-Platzhalter der Folie. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Setzt den Text für den Datum-Uhrzeit-Platzhalter der Folie. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Liest den Wert, der anzeigt, dass ein Fußzeilen-Platzhalter vorhanden ist. Lese boolean.

**Rückgabe:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Liest den Wert, der anzeigt, dass ein Seitenzahl-Platzhalter vorhanden ist. Lese boolean.

**Rückgabe:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Liest den Wert, der anzeigt, dass ein Datum-Uhrzeit-Platzhalter vorhanden ist. Lese boolean.

**Rückgabe:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Fußzeilen-Platzhalters auf der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht den Fußzeilen-Platzhalter sichtbar, sonst - versteckt ihn. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Seitenzahl-Platzhalters auf der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht den Seitenzahl-Platzhalter sichtbar, sonst - versteckt ihn. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters auf der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht den Datum-Uhrzeit-Platzhalter sichtbar, sonst - versteckt ihn. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Setzt den Text für den Fußzeilen-Platzhalter der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Setzt den Text für den Datum-Uhrzeit-Platzhalter der Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |