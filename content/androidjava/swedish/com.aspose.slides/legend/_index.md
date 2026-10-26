---
title: Legend
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar diagrammets legendegenskaper.
type: docs
url: /sv/com.aspose.slides/legend/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILegend](../../com.aspose.slides/ilegend)
```
public class Legend extends DomObject<Chart> implements ILegend
```

Representerar diagrammets legendegenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | Returnerar eller anger x-koordinaten för en legend som en bråkdel av diagrammets bredd. |
| [setX(float value)](#setX-float-) | Returnerar eller anger x-koordinaten för en legend som en bråkdel av diagrammets bredd. |
| [getY()](#getY--) | Returnerar eller anger y-koordinaten för en legend som en bråkdel av diagrammets höjd. |
| [setY(float value)](#setY-float-) | Returnerar eller anger y-koordinaten för en legend som en bråkdel av diagrammets höjd. |
| [getWidth()](#getWidth--) | Returnerar eller anger bredden för en legend som en bråkdel av diagrammets bredd. |
| [setWidth(float value)](#setWidth-float-) | Returnerar eller anger bredden för en legend som en bråkdel av diagrammets bredd. |
| [getHeight()](#getHeight--) | Returnerar eller anger höjden för en legend som en bråkdel av diagrammets höjd. |
| [setHeight(float value)](#setHeight-float-) | Returnerar eller anger höjden för en legend som en bråkdel av diagrammets höjd. |
| [getRight()](#getRight--) | Höger. |
| [getBottom()](#getBottom--) | Nederkant. |
| [getOverlay()](#getOverlay--) | Avgör om andra diagramelement får överlappa legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Avgör om andra diagramelement får överlappa legend. |
| [getTextFormat()](#getTextFormat--) | Textformat. |
| [getPosition()](#getPosition--) | Anger legendens position i ett diagram. |
| [setPosition(int value)](#setPosition-int-) | Anger legendens position i ett diagram. |
| [getFormat()](#getFormat--) | Returnerar formatet för en legend. |
| [getChart()](#getChart--) | Returnerar diagrammet. |
| [getEntries()](#getEntries--) | Hämtar legendposter. |
| [getActualX()](#getActualX--) | Anger den faktiska x-positionen (vänster) för diagram-elementet relativt diagrammets övre vänstra hörn. |
| [getActualY()](#getActualY--) | Anger den faktiska toppen för diagram-elementet relativt diagrammets övre vänstra hörn. |
| [getActualWidth()](#getActualWidth--) | Anger den faktiska bredden för diagram-elementet. |
| [getActualHeight()](#getActualHeight--) | Anger den faktiska höjden för diagram-elementet. |
| [getSlide()](#getSlide--) | Returnerar den överordnade sliden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |
### getX() {#getX--}
```
public final float getX()
```


Returnerar eller anger x-koordinaten för en legend som en bråkdel av diagrammets bredd. Läs/skriv float.

**Returnerar:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Returnerar eller anger x-koordinaten för en legend som en bråkdel av diagrammets bredd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Returnerar eller anger y-koordinaten för en legend som en bråkdel av diagrammets höjd. Läs/skriv float.

**Returnerar:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Returnerar eller anger y-koordinaten för en legend som en bråkdel av diagrammets höjd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returnerar eller anger bredden för en legend som en bråkdel av diagrammets bredd. Läs/skriv float.

**Returnerar:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Returnerar eller anger bredden för en legend som en bråkdel av diagrammets bredd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returnerar eller anger höjden för en legend som en bråkdel av diagrammets höjd. Läs/skriv float.

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returnerar eller anger höjden för en legend som en bråkdel av diagrammets höjd. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```


Höger. Endast läsning float.

**Returnerar:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Nederkant. Endast läsning float.

**Returnerar:**
float
### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```


Avgör om andra diagramelement får överlappa legend. Läs/skriv boolean.

**Returnerar:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```


Avgör om andra diagramelement får överlappa legend. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Textformat. Endast läsning [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returnerar:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Anger legendens position i ett diagram. Icke-NaN-värden för egenskaperna X, Y, Width, Height åsidosätter denna egenskaps effekt. Läs/skriv [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Anger legendens position i ett diagram. Icke-NaN-värden för egenskaperna X, Y, Width, Height åsidosätter denna egenskaps effekt. Läs/skriv [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Returnerar formatet för en legend. Endast läsning [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returnerar diagrammet. Endast läsning [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)
### getEntries() {#getEntries--}
```
public final ILegendEntryCollection getEntries()
```


Hämtar legendposter. Endast läsning [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Returnerar:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Anger den faktiska x-positionen (vänster) för diagram-elementet relativt diagrammets övre vänstra hörn. Anropa metoden IChart.validateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Anger den faktiska toppen för diagram-elementet relativt diagrammets övre vänstra hörn. Anropa metoden IChart.validateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Anger den faktiska bredden för diagram-elementet. Anropa metoden IChart.validateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Anger den faktiska höjden för diagram-elementet. Anropa metoden IChart.validateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returnerar den överordnade sliden för ett FillFormat. Endast läsning [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returnerar den överordnade presentationen för ett FillFormat. Endast läsning [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)