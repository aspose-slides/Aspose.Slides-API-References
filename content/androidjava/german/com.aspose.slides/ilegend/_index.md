---
title: ILegend
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt die Eigenschaften der Diagrammlegende dar.
type: docs
url: /de/com.aspose.slides/ilegend/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Stellt die Legenden-Eigenschaften des Diagramms dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOverlay()](#getOverlay--) | Bestimmt, ob andere Diagrammelemente die Legende überlappen dürfen. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bestimmt, ob andere Diagrammelemente die Legende überlappen dürfen. |
| [getPosition()](#getPosition--) | Gibt die Position der Legende in einem Diagramm an. |
| [setPosition(int value)](#setPosition-int-) | Gibt die Position der Legende in einem Diagramm an. |
| [getFormat()](#getFormat--) | Gibt das Format einer Legende zurück. |
| [getEntries()](#getEntries--) | Ermittelt die Legendeinträge. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Bestimmt, ob andere Diagrammelemente die Legende überlappen dürfen. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Bestimmt, ob andere Diagrammelemente die Legende überlappen dürfen. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Gibt die Position der Legende in einem Diagramm an. Nicht-NaN-Werte der Eigenschaften X, Y, Width, Heigt überschreiben die Wirkung dieser Eigenschaft. Lese/Schreib [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Rückgabewert:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Gibt die Position der Legende in einem Diagramm an. Nicht-NaN-Werte der Eigenschaften X, Y, Width, Heigt überschreiben die Wirkung dieser Eigenschaft. Lese/Schreib [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Gibt das Format einer Legende zurück. Nur lesbar [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Ermittelt die Legendeinträge. Nur lesbar [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Rückgabewert:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)