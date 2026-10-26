---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt den Manager dar, der das Verhalten der Platzhalter enthält, einschließlich des Header-Platzhalters für alle Arten von Handout- und Notizfolien.
type: docs
url: /de/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Stellt den Manager dar, der das Verhalten der Platzhalter enthält, einschließlich des Header-Platzhalters für alle Arten von Handout- und Notizfolien.

--------------------

Der ursprüngliche Schnittstellenname "IBaseHandoutNotesSlideHeaderFooterManager" wird für COM-Kompatibilität auf "IBaseHandoutNotesSlideHeaderFooterManag" verkürzt (die Namenslänge darf nicht mehr als 39 Zeichen betragen).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Gibt einen Wert zurück, der anzeigt, dass ein Header-Platzhalter vorhanden ist. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Ändert die Sichtbarkeit des Folien-Header-Platzhalters. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Setzt den Text für den Folien-Header-Platzhalter. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Gibt einen Wert zurück, der anzeigt, dass ein Header-Platzhalter vorhanden ist. Boolescher Wert lesen.

**Rückgabe:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Ändert die Sichtbarkeit des Folien-Header-Platzhalters.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true - macht einen Header-Platzhalter sichtbar, sonst - blendet ihn aus. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Setzt Text für den Folien-Header-Platzhalter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |