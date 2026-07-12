---
title: ChartDataPoint
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt einen Datenpunkt der Serie dar.
type: docs
url: /de/com.aspose.slides/chartdatapoint/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Stellt einen Datenpunkt der Serie dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Gibt den Größenwert des Diagrammdatenpunkts zurück. |
| [getColorValue()](#getColorValue--) | Gibt den Farbwert des Diagrammdatenpunkts zurück. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stellt die Werte der Fehlerbalken der Serie im Fall des benutzerdefinierten Wertetyps dar. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [getExplosion()](#getExplosion--) | Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kreisdiagramms verschoben wird. |
| [setExplosion(int value)](#setExplosion-int-) | Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kreisdiagramms verschoben wird. |
| [getFormat()](#getFormat--) | Stellt die Formatierungseigenschaften dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt die Formatierungseigenschaften dar. |
| [getMarker()](#getMarker--) | Gibt einen Datenmarker an. |
| [getSetAsTotal()](#getSetAsTotal--) | Setzt den Datenpunkt als Gesamtsumme. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Setzt den Datenpunkt als Gesamtsumme. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschaften des zugehörigen Legendeneintrags für Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Entfernt den Datenpunkt aus der Diagrammserie. |
| [getDataPointLevels()](#getDataPointLevels--) | Gibt den Container der Datenpunktstufen zurück. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf Serien-Index, Datenpunkt-Index, ParentSeriesGroup.IsColorVaried-Eigenschaft und Diagrammstil. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. |
| [getActualX()](#getActualX--) | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualY()](#getActualY--) | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualWidth()](#getActualWidth--) | Gibt die tatsächliche Breite des Diagrammelements an. |
| [getActualHeight()](#getActualHeight--) | Gibt die tatsächliche Höhe des Diagrammelements an. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Nur lesbar [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Rückgabewert:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabewert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabewert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabewert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Gibt den Größenwert des Diagrammdatenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabewert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Gibt den Farbwert des Diagrammdatenpunkts zurück. Wird mit Karten-Diagrammen verwendet. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabewert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Stellt die Werte der Fehlerbalken der Serie im Fall des benutzerdefinierten Wertetyps dar. Nur lesbar [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Rückgabewert:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Nur lesbar [IDataLabel](../../com.aspose.slides/idatalabel).

**Rückgabewert:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese-/Schreibzugriff boolesch.

**Rückgabewert:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese-/Schreibzugriff boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kreisdiagramms verschoben wird. Lese-/Schreibzugriff int.

**Rückgabewert:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kreisdiagramms verschoben wird. Lese-/Schreibzugriff int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stellt die Formatierungseigenschaften dar. Lese-/Schreibzugriff [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stellt die Formatierungseigenschaften dar. Lese-/Schreibzugriff [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Gibt einen Datenmarker an. Nur lesbar [IMarker](../../com.aspose.slides/imarker).

**Rückgabewert:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Setzt den Datenpunkt als Gesamtsumme. Wird nur für den Waterfall-Serientyp angewendet.

**Rückgabewert:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Setzt den Datenpunkt als Gesamtsumme. Wird nur für den Waterfall-Serientyp angewendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschaften des zugehörigen Legendeneintrags für Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabewert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Entfernt den Datenpunkt aus der Diagrammserie.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Gibt den Container der Datenpunktstufen zurück. Wird für Treeamp- und Sunburst-Serien verwendet. Die Indizierung der Datenpunktstufen beginnt bei Null.

**Rückgabewert:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**Rückgabewert:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf Serien-Index, Datenpunkt-Index, ParentSeriesGroup.IsColorVaried-Eigenschaft und Diagrammstil. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist.

**Rückgabewert:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lese-/Schreibzugriff boolesch.

**Rückgabewert:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lese-/Schreibzugriff boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabewert:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabewert:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabewert:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabewert:**
float