---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides für Java API-Referenz
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

Der ursprüngliche Schnittstellenname "IBaseHandoutNotesSlideHeaderFooterManager" wurde aus COM-Kompatibilitätsgründen auf "IBaseHandoutNotesSlideHeaderFooterManag" verkürzt (der Typname darf nicht länger als 39 Zeichen sein).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Gibt den Wert zurück, der angibt, dass ein Header-Platzhalter vorhanden ist. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Ändert die Sichtbarkeit des Folien-Header-Platzhalters. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Setzt den Text für den Folien-Header-Platzhalter. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Gibt den Wert zurück, der angibt, dass ein Header-Platzhalter vorhanden ist. Lese boolean.

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
| isVisible | boolean | true - macht einen Header-Platzhalter sichtbar, andernfalls - versteckt ihn. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Setzt den Text für den Folien-Header-Platzhalter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |