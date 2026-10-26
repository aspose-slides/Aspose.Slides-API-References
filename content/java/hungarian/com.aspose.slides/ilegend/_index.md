---
title: ILegend
second_title: Aspose.Slides Java API hivatkozás
description: A diagram jelmagyarázatának tulajdonságait reprezentálja.
type: docs
url: /hu/com.aspose.slides/ilegend/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

A diagram jelmagyarázatának tulajdonságait reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOverlay()](#getOverlay--) | Meghatározza, hogy a diagram többi eleme átfedheti-e a jelmagyarázatot. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Meghatározza, hogy a diagram többi eleme átfedheti-e a jelmagyarázatot. |
| [getPosition()](#getPosition--) | Megadja a jelmagyarázat helyzetét a diagramon. |
| [setPosition(int value)](#setPosition-int-) | Megadja a jelmagyarázat helyzetét a diagramon. |
| [getFormat()](#getFormat--) | Visszaadja a jelmagyarázat formátumát. |
| [getEntries()](#getEntries--) | Lekéri a jelmagyarázat bejegyzéseit. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Meghatározza, hogy a diagram többi eleme átfedheti-e a jelmagyarázatot. Olvasás/írás bool.

**Visszatér:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Meghatározza, hogy a diagram többi eleme átfedheti-e a jelmagyarázatot. Olvasás/írás bool.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Megadja a jelmagyarázat helyzetét a diagramon. A X, Y, Width és Heigt tulajdonságok nem NaN értékei felülírják ennek a tulajdonságnak a hatását. Olvasás/írás [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Visszatér:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Megadja a jelmagyarázat helyzetét a diagramon. A X, Y, Width és Heigt tulajdonságok nem NaN értékei felülírják ennek a tulajdonságnak a hatását. Olvasás/írás [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a jelmagyarázat formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Lekéri a jelmagyarázat bejegyzéseit. Csak olvasható [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Visszatér:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)