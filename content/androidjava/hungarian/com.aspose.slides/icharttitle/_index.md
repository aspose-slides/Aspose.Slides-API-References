---
title: IChartTitle
second_title: Aspose.Slides for Android Java API hivatkozás
description: A diagramcím tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/icharttitle/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

A diagramcím tulajdonságait képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOverlay()](#getOverlay--) | Megállapítja, hogy a diagram egyéb elemei átfedhetik-e a címet. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Megállapítja, hogy a diagram egyéb elemei átfedhetik-e a címet. |
| [getFormat()](#getFormat--) | Visszaadja a cím kitöltési, vonal- és effektusstílusait. |

### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Megállapítja, hogy a diagram egyéb elemei átfedhetik-e a címet. Olvasás/írás boolean.

**Visszatér:**
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Megállapítja, hogy a diagram egyéb elemei átfedhetik-e a címet. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a cím kitöltési, vonal- és effektusstílusait. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)