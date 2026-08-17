---
title: ChartDataPoint
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Seriendatenpunkt dar.
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

Stellt ein Seriendatenpunkt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Gibt den Größenwert des Diagrammdatenpunkts zurück. |
| [getColorValue()](#getColorValue--) | Gibt den Farbwert des Diagrammdatenpunkts zurück. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stellt Serien-Fehlerbalkenwerte im Fall des benutzerdefinierten Werttyps dar. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [getExplosion()](#getExplosion--) | Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. |
| [setExplosion(int value)](#setExplosion-int-) | Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. |
| [getFormat()](#getFormat--) | Stellt die Formatierungseigenschaften dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt die Formatierungseigenschaften dar. |
| [getMarker()](#getMarker--) | Gibt einen Datenmarker an. |
| [getSetAsTotal()](#getSetAsTotal--) | Setzt Datenpunkt als Gesamtwert. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Setzt Datenpunkt als Gesamtwert. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschaften des entsprechenden Legendeneintrags im Fall von Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Entfernt DataPoint aus der Diagrammserie. |
| [getDataPointLevels()](#getDataPointLevels--) | Gibt den Container der Datenpunktenebenen zurück. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Gibt eine automatische Farbe des Datenpunkts basierend auf Serienindex, Datenpunktindex, ParentSeriesGroup.IsColorVaried-Eigenschaft und Diagrammstil zurück. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. |
| [getActualX()](#getActualX--) | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualY()](#getActualY--) | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualWidth()](#getActualWidth--) | Gibt die tatsächliche Breite des Diagrammelements an. |
| [getActualHeight()](#getActualHeight--) | Gibt die tatsächliche Höhe des Diagrammelements an. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Schreibgeschützt [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Rückgabe:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Schreibgeschützt [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Schreibgeschützt [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Schreibgeschützt [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Gibt den Größenwert des Diagrammdatenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Schreibgeschützt [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Gibt den Farbwert des Diagrammdatenpunkts zurück. Wird mit Karten-Diagrammen verwendet. Schreibgeschützt [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Stellt Serien-Fehlerbalkenwerte im Fall des benutzerdefinierten Werttyps dar. Schreibgeschützt [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Rückgabe:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Schreibgeschützt [IDataLabel](../../com.aspose.slides/idatalabel).

**Rückgabe:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese-/Schreib-Zugriff boolean.

**Rückgabe:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese-/Schreib-Zugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. Lese-/Schreib-Zugriff int.

**Rückgabe:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. Lese-/Schreib-Zugriff int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Stellt die Formatierungseigenschaften dar. Lese-/Schreib-Zugriff [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Stellt die Formatierungseigenschaften dar. Lese-/Schreib-Zugriff [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Gibt einen Datenmarker an. Schreibgeschützt [IMarker](../../com.aspose.slides/imarker).

**Rückgabe:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Setzt Datenpunkt als Gesamtwert. Wird nur für Waterfall-Serientyp verwendet.

**Rückgabe:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Setzt Datenpunkt als Gesamtwert. Wird nur für Waterfall-Serientyp verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Eigenschaften des entsprechenden Legendeneintrags im Fall von Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Schreibgeschützt [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


Entfernt DataPoint aus der Diagrammserie.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Gibt den Container der Datenpunktenebenen zurück. Wird für Treeamp- und Sunburst-Serien verwendet. Die Indizierung der Datenpunktenebenen beginnt bei Null.

**Rückgabe:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Rückgabe:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Schreibgeschützt IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```


Gibt eine automatische Farbe des Datenpunkts basierend auf Serienindex, Datenpunktindex, ParentSeriesGroup.IsColorVaried-Eigenschaft und Diagrammstil zurück. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist.

**Rückgabe:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lese-/Schreib-Zugriff boolean.

**Rückgabe:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lese-/Schreib-Zugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabe:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabe:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabe:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Lese-float.

**Rückgabe:**
float