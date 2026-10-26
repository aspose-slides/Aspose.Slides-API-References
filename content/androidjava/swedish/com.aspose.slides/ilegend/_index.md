---
title: ILegend
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar diagrammets legendegenskaper.
type: docs
url: /sv/com.aspose.slides/ilegend/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Representerar diagrammets legendegenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOverlay()](#getOverlay--) | Bestämmer om andra diagramdelar får överlappa legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bestämmer om andra diagramdelar får överlappa legend. |
| [getPosition()](#getPosition--) | Anger legendens position på ett diagram. |
| [setPosition(int value)](#setPosition-int-) | Anger legendens position på ett diagram. |
| [getFormat()](#getFormat--) | Returnerar formatet för en legend. |
| [getEntries()](#getEntries--) | Hämtar legendposter. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Bestämmer om andra diagramdelar får överlappa legend. Läs/skriv boolean.

**Returnerar:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Bestämmer om andra diagramdelar får överlappa legend. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Anger legendens position på ett diagram. Icke-NaN-värden för X, Y, Width, Heigt-egenskaperna åsidosätter effekten av denna egenskap. Läs/skriv [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Anger legendens position på ett diagram. Icke-NaN-värden för X, Y, Width, Heigt-egenskaperna åsidosätter effekten av denna egenskap. Läs/skriv [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returnerar formatet för en legend. Skrivskyddad [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Hämtar legendposter. Skrivskyddad [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Returnerar:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)