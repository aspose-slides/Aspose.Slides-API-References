---
title: ChartDataPoint
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Datenpunkt einer Serie dar.
type: docs
url: /de/com.aspose.slides/chartdatapoint/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Stellt einen Serien-Datenpunkt dar.
## Methoden

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Gibt den Größewert des Diagrammdatenpunkts zurück. |
| [getColorValue()](#getColorValue--) | Gibt den Farbwert des Diagrammdatenpunkts zurück. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stellt die Fehlerbalkenwerte der Serie im Fall des benutzerdefinierten Werttyps dar. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [getExplosion()](#getExplosion--) | Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. |
| [setExplosion(int value)](#setExplosion-int-) | Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. |
| [getFormat()](#getFormat--) | Stellt die Formatierungseigenschaften dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt die Formatierungseigenschaften dar. |
| [getMarker()](#getMarker--) | Gibt einen Datenmarker an. |
| [getSetAsTotal()](#getSetAsTotal--) | Setzt den Datenpunkt als Gesamtsumme. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Setzt den Datenpunkt als Gesamtsumme. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschaften des entsprechenden Legendeneintrags im Fall von Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Entfernt DataPoint aus der Diagrammserie. |
| [getDataPointLevels()](#getDataPointLevels--) | Gibt den Container der Datenpunkteniveaus zurück. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf Serien-Index, Datenpunkt-Index, ParentSeriesGroup.IsColorVaried-Eigenschaft und Diagrammstil. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. |
| [getCachedValue()](#getCachedValue--) | Gibt den zwischengespeicherten Wert eines Diagrammdatenpunkts zurück. |
| [getCachedXValue()](#getCachedXValue--) | Gibt den zwischengespeicherten X-Wert eines Diagrammdatenpunkts zurück. |
| [getCachedYValue()](#getCachedYValue--) | Gibt den zwischengespeicherten Y-Wert eines Diagrammdatenpunkts zurück. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Gibt die zwischengespeicherte Blasengröße eines Diagrammdatenpunkts zurück. |
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


Gibt den Größewert des Diagrammdatenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

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


Stellt die Fehlerbalkenwerte der Serie im Fall des benutzerdefinierten Werttyps dar. Nur lesbar [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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


Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese/Schreib boolesch.

**Rückgabewert:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. Lese/Schreib int.

**Rückgabewert:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Gibt an, um welchen Betrag der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. Lese/Schreib int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Stellt die Formatierungseigenschaften dar. Lese/Schreib [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Stellt die Formatierungseigenschaften dar. Lese/Schreib [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```
Legt einen Datenmarker fest. Nur lesbar [IMarker](../../com.aspose.slides/imarker).

**Rückgabe:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Setzt den Datenpunkt als Gesamtsumme. Nur für den Serien-Typ Waterfall anwendbar.

**Rückgabe:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Setzt den Datenpunkt als Gesamtsumme. Nur für den Serien-Typ Waterfall anwendbar.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschaften des entsprechenden Legendeneintrags für Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Gibt den Container der Datenpunkt-Ebenen zurück. Gilt für die Serien Treeamp und Sunburst. Die Indizierung der Datenpunkt-Ebenen ist nullbasiert.

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

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serien-Index, dem Datenpunkt-Index, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist.

**Rückgabe:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Legt fest, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Legt fest, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Liest den zwischengespeicherten Wert eines Diagrammdatenpunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Gibt alle zwischengespeicherten Werte der Diagrammserie aus.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Liest den zwischengespeicherten X-Wert eines Diagrammdatenpunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Gibt alle zwischengespeicherten X-Werte der Diagrammserie aus.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

Liest den zwischengespeicherten Y-Wert eines Diagrammdatenpunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Gibt alle zwischengespeicherten Y-Werte der Diagrammserie aus.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Liest die zwischengespeicherte Bubble-Größe eines Diagrammdatenpunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Gibt alle zwischengespeicherten Blasengrößenwerte der Diagrammserie aus.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Nur lesbar float.

**Rückgabe:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Nur lesbar float.

**Rückgabe:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Nur lesbar float.

**Rückgabe:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorab die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Nur lesbar float.

**Rückgabe:**
float