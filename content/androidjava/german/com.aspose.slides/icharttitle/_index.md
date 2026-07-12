---
title: IChartTitle
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getOverlay()](#getOverlay--) | Bestimmt, ob anderen Diagrammelementen das Überlappen des Titels erlaubt sein soll. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bestimmt, ob anderen Diagrammelementen das Überlappen des Titels erlaubt sein soll. |
| [getFormat()](#getFormat--) | Gibt die Füll-, Linien- und Effektstile eines Titels zurück. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Bestimmt, ob anderen Diagrammelementen das Überlappen des Titels erlaubt sein soll. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Bestimmt, ob anderen Diagrammelementen das Überlappen des Titels erlaubt sein soll. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Gibt die Füll-, Linien- und Effektstile eines Titels zurück. Nur-Lese [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)