---
title: IChartTitle
second_title: Aspose.Slides Java API Referenciája
description: A diagramcím tulajdonságait ábrázolja.
type: docs
url: /hu/com.aspose.slides/icharttitle/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

A diagramcím tulajdonságait ábrázolja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOverlay()](#getOverlay--) | Megállapítja, hogy más diagramelemek átfedhetik-e a címet. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Megállapítja, hogy más diagramelemek átfedhetik-e a címet. |
| [getFormat()](#getFormat--) | Visszaadja a cím kitöltés, vonal és effekt stílusait. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Megállapítja, hogy más diagramelemek átfedhetik-e a címet. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Megállapítja, hogy más diagramelemek átfedhetik-e a címet. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Visszaadja a cím kitöltés, vonal és effekt stílusait. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)