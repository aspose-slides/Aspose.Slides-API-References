---
title: IChartTitle
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Eigenschaften des Diagrammtitels dar.
type: docs
url: /de/com.aspose.slides/icharttitle/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Stellt die Eigenschaften des Diagrammtitels dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOverlay()](#getOverlay--) | Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. |
| [getFormat()](#getFormat--) | Gibt die Füll-, Linien- und Effektstile eines Titels zurück. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. Lese-/Schreib-Boolean.

**Rückgabe:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. Lese-/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Gibt die Füll-, Linien- und Effektstile eines Titels zurück. Nur lesbar [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)