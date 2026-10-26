---
title: IChartDataPoint
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt einen Datenpunkt einer Serie dar.
type: docs
url: /de/com.aspose.slides/ichartdatapoint/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Stellt ein Datenpunkt einer Serie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXValue()](#getXValue--) | Gibt den x-Wert des Diagrammdatenpunkts zurück. |
| [getYValue()](#getYValue--) | Gibt den y-Wert des Diagrammdatenpunkts zurück. |
| [getBubbleSize()](#getBubbleSize--) | Gibt die Bubble-Groesse des Diagrammdatenpunkts zurueck. |
| [getValue()](#getValue--) | Gibt den Wert des Diagrammdatenpunkts zurueck. |
| [getSizeValue()](#getSizeValue--) | Gibt den Groessenwert des Diagrammdatenpunkts zurueck. |
| [getColorValue()](#getColorValue--) | Gibt den Farbwert des Diagrammdatenpunkts zurueck. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stellt die Fehlerbalkenwerte der Serie dar, falls der Werttyp Custom ist. |
| [getLabel()](#getLabel--) | Stellt die Beschriftung des Diagrammdatenpunkts dar. |
| [isBubble3D()](#isBubble3D--) | Gibt an, dass die Bubbles einen 3-D-Effekt erhalten. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Gibt an, dass die Bubbles einen 3-D-Effekt erhalten. |
| [getExplosion()](#getExplosion--) | Gibt die Menge an, um die der Datenpunkt vom Mittelpunkt des Kuchens verschoben wird. |
| [setExplosion(int value)](#setExplosion-int-) | Gibt die Menge an, um die der Datenpunkt vom Mittelpunkt des Kuchens verschoben wird. |
| [getFormat()](#getFormat--) | Stellt die Formatierungseigenschaften dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt die Formatierungseigenschaften dar. |
| [getMarker()](#getMarker--) | Gibt einen Datenmarker an. |
| [remove()](#remove--) | Entfernt den Datenpunkt aus der Diagrammserie. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Gibt die automatische Farbe des Datenpunkts basierend auf Serienindex, Datenpunktindex, ParentSeriesGroup.IsColorVaried-Eigenschaft und Diagrammstil zurueck. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschaften des entsprechenden Legendeintrags fuer Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Setzt den Datenpunkt als Gesamtsumme. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Setzt den Datenpunkt als Gesamtsumme. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. |
| [getDataPointLevels()](#getDataPointLevels--) | Gibt den Container der Datenpunkt-Ebenen zurueck. |
| [getIndex()](#getIndex--) | Bestimmt, zu welcher Kindersammlung des Elternteils dieser Datenpunkt gehoert. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Gibt den x-Wert des Diagrammdatenpunkts zurueck. Nur-Lesen [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Ruckgabe:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Gibt den y-Wert des Diagrammdatenpunkts zurueck. Nur-Lesen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ruckgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Gibt die Bubble-Groesse des Diagrammdatenpunkts zurueck. Nur-Lesen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ruckgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Gibt den Wert des Diagrammdatenpunkts zurueck. Nur-Lesen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ruckgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Gibt den Groessenwert des Diagrammdatenpunkts zurueck. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur-Lesen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ruckgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Gibt den Farbwert des Diagrammdatenpunkts zurueck. Wird mit Map-Diagrammen verwendet. Nur-Lesen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ruckgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Stellt die Fehlerbalkenwerte der Serie dar, falls der Werttyp Custom ist. Nur-Lesen [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Ruckgabe:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Stellt die Beschriftung des Diagrammdatenpunkts dar. Nur-Lesen [IDataLabel](../../com.aspose.slides/idatalabel).

**Ruckgabe:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Gibt an, dass die Bubbles einen 3-D-Effekt erhalten. Lese/Schreib boolesch.

**Ruckgabe:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Gibt an, dass die Bubbles einen 3-D-Effekt erhalten. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Gibt die Menge an, um die der Datenpunkt vom Mittelpunkt des Kuchens verschoben wird. Lese/Schreib int.

**Ruckgabe:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Gibt die Menge an, um die der Datenpunkt vom Mittelpunkt des Kuchens verschoben wird. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt die Formatierungseigenschaften dar. Lese/Schreib [IFormat](../../com.aspose.slides/iformat).

**Ruckgabe:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Stellt die Formatierungseigenschaften dar. Lese/Schreib [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Gibt einen Datenmarker an. Nur-Lesen [IMarker](../../com.aspose.slides/imarker).

**Ruckgabe:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den Datenpunkt aus der Diagrammserie.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Gibt eine automatische Farbe des Datenpunkts zurueck, basierend auf Serienindex, Datenpunktindex, ParentSeriesGroup.IsColorVaried-Eigenschaft und Diagrammstil. Diese Farbe wird standardmaessig verwendet, wenn FillType gleich NotDefined ist.

**Ruckgabe:**
java.lang.Integer - Automatische Farbe des Datenpunkts java.lang.Integer

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschaften des entsprechenden Legendeintrags fuer Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur-Lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Ruckgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Setzt den Datenpunkt als Gesamtsumme. Wird nur fuer Waterfall-Serientyp verwendet.

**Ruckgabe:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Setzt den Datenpunkt als Gesamtsumme. Wird nur fuer Waterfall-Serientyp verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lese/Schreib boolesch.

**Ruckgabe:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Gibt den Container der Datenpunkt-Ebenen zurueck. Wird fuer Treeamp- und Sunburst-Serien verwendet. Die Indizierung der Datenpunktenebenen beginnt bei Null.

**Ruckgabe:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bestimmt, zu welcher Kindersammlung des Elternteils dieser Datenpunkt gehoert. Nur-Lesen long.

**Ruckgabe:**
long