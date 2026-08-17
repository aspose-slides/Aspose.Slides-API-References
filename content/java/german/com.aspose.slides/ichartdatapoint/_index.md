---
title: IChartDataPoint
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Datenpunkt der Serie dar.
type: docs
url: /de/com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Stellt einen Datenpunkt der Serie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXValue()](#getXValue--) | Gibt den x-Wert des Diagrammdatapunkts zurück. |
| [getYValue()](#getYValue--) | Gibt den y-Wert des Diagrammdatapunkts zurück. |
| [getBubbleSize()](#getBubbleSize--) | Gibt die Blasengröße des Diagrammdatapunkts zurück. |
| [getValue()](#getValue--) | Gibt den Wert des Diagrammdatapunkts zurück. |
| [getSizeValue()](#getSizeValue--) | Gibt den Größenwert des Diagrammdatapunkts zurück. |
| [getColorValue()](#getColorValue--) | Gibt den Farbwert des Diagrammdatapunkts zurück. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stellt die Werte der Fehlerbalken der Serie dar, falls der Werttyp Custom ist. |
| [getLabel()](#getLabel--) | Stellt die Beschriftung des Diagrammdatapunkts dar. |
| [isBubble3D()](#isBubble3D--) | Gibt an, dass die Blasen einen 3-D-Effekt haben. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Gibt an, dass die Blasen einen 3-D-Effekt haben. |
| [getExplosion()](#getExplosion--) | Gibt die Menge an, um die der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. |
| [setExplosion(int value)](#setExplosion-int-) | Gibt die Menge an, um die der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. |
| [getFormat()](#getFormat--) | Stellt die Formatierungseigenschaften dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt die Formatierungseigenschaften dar. |
| [getMarker()](#getMarker--) | Gibt einen Datenmarker an. |
| [remove()](#remove--) | Entfernt den DataPoint aus der Diagrammreihe. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschaften des entsprechenden Legendeneintrags für Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Setzt den Datenpunkt als Gesamtsumme. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Setzt den Datenpunkt als Gesamtsumme. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. |
| [getDataPointLevels()](#getDataPointLevels--) | Gibt den Container der Datenpunkt-Level zurück. |
| [getIndex()](#getIndex--) | Bestimmt, auf welche Kindersammlung des übergeordneten Elements dieser Datenpunkt angewendet wird. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Gibt den x-Wert des Diagrammdatapunkts zurück. Nur lesbar [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Rückgabe:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Gibt den y-Wert des Diagrammdatapunkts zurück. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Gibt die Blasengröße des Diagrammdatapunkts zurück. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Gibt den Wert des Diagrammdatapunkts zurück. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Gibt den Größenwert des Diagrammdatapunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Gibt den Farbwert des Diagrammdatapunkts zurück. Wird mit Karten-Diagrammen verwendet. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Stellt die Werte der Fehlerbalken der Serie dar, falls der Werttyp Custom ist. Nur lesbar [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Rückgabe:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Stellt die Beschriftung des Diagrammdatapunkts dar. Nur lesbar [IDataLabel](../../com.aspose.slides/idatalabel).

**Rückgabe:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Gibt an, dass die Blasen einen 3-D-Effekt haben. Lese-/Schreib-boolesch.

**Rückgabe:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Gibt an, dass die Blasen einen 3-D-Effekt haben. Lese-/Schreib-boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Gibt die Menge an, um die der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. Lese-/Schreib-int.

**Rückgabe:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Gibt die Menge an, um die der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. Lese-/Schreib-int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt die Formatierungseigenschaften dar. Lese-/Schreib-[IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Stellt die Formatierungseigenschaften dar. Lese-/Schreib-[IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Gibt einen Datenmarker an. Nur lesbar [IMarker](../../com.aspose.slides/imarker).

**Rückgabe:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den DataPoint aus der Diagrammreihe.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist.

**Rückgabe:**
java.awt.Color - Automatic color of data point java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschaften des entsprechenden Legendeneintrags für Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Setzt den Datenpunkt als Gesamtsumme. Wird nur für den Serientyp Waterfall angewendet.

**Rückgabe:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Setzt den Datenpunkt als Gesamtsumme. Wird nur für den Serientyp Waterfall angewendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lese-/Schreib-boolesch.

**Rückgabe:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lese-/Schreib-boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Gibt den Container der Datenpunkt-Level zurück. Wird für TreeMap- und Sunburst-Serien angewendet. Die Indizierung der Datenpunkt-Level beginnt bei null.

**Rückgabe:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bestimmt, auf welche Kindersammlung des übergeordneten Elements dieser Datenpunkt angewendet wird. Lese-long.

**Rückgabe:**
long