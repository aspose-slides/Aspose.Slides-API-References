---
title: IChartDataPoint
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Datenpunkt einer Serie dar.
type: docs
url: /de/com.aspose.slides/ichartdatapoint/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Repräsentiert einen Datenpunkt einer Serie.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXValue()](#getXValue--) | Ermittelt den x-Wert eines Diagrammdatapunkts. |
| [getYValue()](#getYValue--) | Ermittelt den y-Wert eines Diagrammdatapunkts. |
| [getBubbleSize()](#getBubbleSize--) | Ermittelt die Blasengröße eines Diagrammdatapunkts. |
| [getValue()](#getValue--) | Ermittelt den Wert eines Diagrammdatapunkts. |
| [getCachedXValue()](#getCachedXValue--) | Ermittelt den zwischengespeicherten X-Wert eines Diagrammdatapunkts. |
| [getCachedYValue()](#getCachedYValue--) | Ermittelt den zwischengespeicherten Y-Wert eines Diagrammdatapunkts. |
| [getCachedValue()](#getCachedValue--) | Ermittelt den zwischengespeicherten Wert eines Diagrammdatapunkts. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Ermittelt die zwischengespeicherte Blasengröße eines Diagrammdatapunkts. |
| [getSizeValue()](#getSizeValue--) | Ermittelt den Größenwert eines Diagrammdatapunkts. |
| [getColorValue()](#getColorValue--) | Ermittelt den Farbwert eines Diagrammdatapunkts. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stellt die Werte der Serien-Fehlerbalken im Fall des benutzerdefinierten Wertetyps dar. |
| [getLabel()](#getLabel--) | Stellt das Etikett eines Diagrammdatapunkts dar. |
| [isBubble3D()](#isBubble3D--) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. |
| [getExplosion()](#getExplosion--) | Gibt den Betrag an, um den der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. |
| [setExplosion(int value)](#setExplosion-int-) | Gibt den Betrag an, um den der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. |
| [getFormat()](#getFormat--) | Stellt die Formatierungseigenschaften dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt die Formatierungseigenschaften dar. |
| [getMarker()](#getMarker--) | Gibt einen Datenmarker an. |
| [remove()](#remove--) | Entfernt den Datenpunkt aus der Diagrammserie. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Gibt eine automatische Farbe des Datenpunkts basierend auf dem Index der Serie, dem Index des Datenpunkts, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil zurück. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschaften des entsprechenden Legendeneintrags für Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Setzt den Datenpunkt als Gesamtsumme. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Setzt den Datenpunkt als Gesamtsumme. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. |
| [getDataPointLevels()](#getDataPointLevels--) | Gibt den Container der Datenpunktstufen zurück. |
| [getIndex()](#getIndex--) | Bestimmt, zu welcher Kindersammlung des übergeordneten Elements dieser Datenpunkt gehört. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Ermittelt den x-Wert eines Diagrammdatapunkts. Nur lesbar [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Rückgabe:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Ermittelt den y-Wert eines Diagrammdatapunkts. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Ermittelt die Blasengröße eines Diagrammdatapunkts. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Ermittelt den Wert eines Diagrammdatapunkts. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

Ermittelt den zwischengespeicherten X-Wert eines Diagrammdatapunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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
public abstract ICachedChartValue getCachedYValue()
```

Ermittelt den zwischengespeicherten Y-Wert eines Diagrammdatapunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Ermittelt den zwischengespeicherten Wert eines Diagrammdatapunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

Ermittelt die zwischengespeicherte Blasengröße eines Diagrammdatapunkts. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Ermittelt den Größenwert eines Diagrammdatapunkts. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Ermittelt den Farbwert eines Diagrammdatapunkts. Wird mit Karten-Diagrammen verwendet. Nur lesbar [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Rückgabe:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Stellt die Werte der Serien-Fehlerbalken im Fall des benutzerdefinierten Wertetyps dar. Nur lesbar [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Rückgabe:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Stellt das Etikett eines Diagrammdatapunkts dar. Nur lesbar [IDataLabel](../../com.aspose.slides/idatalabel).

**Rückgabe:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese/Schreib boolescher Wert.

**Rückgabe:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lese/Schreib boolescher Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Gibt den Betrag an, um den der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. Lese/Schreib int.

**Rückgabe:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Gibt den Betrag an, um den der Datenpunkt vom Zentrum des Kuchendiagramms verschoben werden soll. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt die Formatierungseigenschaften dar. Lese/Schreib [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
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

Gibt einen Datenmarker an. Nur lesbar [IMarker](../../com.aspose.slides/imarker).

**Rückgabe:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den Datenpunkt aus der Diagrammserie.

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

Setzt den Datenpunkt als Gesamtsumme. Gilt nur für den Waterfall-Serientyp.

**Rückgabe:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Setzt den Datenpunkt als Gesamtsumme. Gilt nur für den Waterfall-Serientyp.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lese/Schreib boolescher Wert.

**Rückgabe:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lese/Schreib boolescher Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Gibt den Container der Datenpunktstufen zurück. Wird für Treeamp- und Sunburst-Serien verwendet. Die Indexierung der Datenpunktstufen beginnt bei Null.

**Rückgabe:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bestimmt, zu welcher Kindersammlung des übergeordneten Elements dieser Datenpunkt gehört. Lese long.

**Rückgabe:**
long