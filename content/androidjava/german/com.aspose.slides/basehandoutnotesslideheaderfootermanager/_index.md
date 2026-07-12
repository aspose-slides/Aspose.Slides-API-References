---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Manager dar, der das Verhalten der Platzhalter verwaltet, einschließlich des Header-Platzhalters für alle Arten von Handout- und Notizfolien.
type: docs
url: /de/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Stellt einen Manager dar, der das Verhalten der Platzhalter verwaltet, einschließlich des Header-Platzhalters für alle Typen von Handout- und Notizfolien.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Ruft den Wert ab, der anzeigt, dass ein Header-Platzhalter vorhanden ist. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Ändert die Sichtbarkeit des Folien-Header-Platzhalters. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Setzt den Text für den Folien-Header-Platzhalter. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```


Ruft den Wert ab, der anzeigt, dass ein Header-Platzhalter vorhanden ist. Leseboolescher Wert.

**Rückgabewert:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```


Ändert die Sichtbarkeit des Folien-Header-Platzhalters.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | true – macht einen Header-Platzhalter sichtbar, andernfalls – versteckt ihn. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```


Setzt den Text für den Folien-Header-Platzhalter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Zu setzender Text. |