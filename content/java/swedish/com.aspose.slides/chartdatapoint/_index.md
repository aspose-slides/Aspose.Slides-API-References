---
title: ChartDataPoint
second_title: Aspose.Slides för Java API-referens
description: Representerar en seriedatapunkt.
type: docs
url: /sv/com.aspose.slides/chartdatapoint/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Representerar en seriedatapunkt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returnerar storleksvärdet för diagramdatapunkten. |
| [getColorValue()](#getColorValue--) | Returnerar färgvärdet för diagramdatapunkten. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representerar seriernas felstaplarvärden i fall av anpassad värdetyp. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Anger att bubblorna har en 3D-effekt tillämpad på dem. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Anger att bubblorna har en 3D-effekt tillämpad på dem. |
| [getExplosion()](#getExplosion--) | Anger hur mycket datapunkten ska flyttas från mitten av pajen. |
| [setExplosion(int value)](#setExplosion-int-) | Anger hur mycket datapunkten ska flyttas från mitten av pajen. |
| [getFormat()](#getFormat--) | Representerar formateringsegenskaperna. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representerar formateringsegenskaperna. |
| [getMarker()](#getMarker--) | Anger en datamarkör. |
| [getSetAsTotal()](#getSetAsTotal--) | Sätter datapunkt som total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Sätter datapunkt som total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Egenskaper för motsvarande legendpost för diagramtyper från följande lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Tar bort DataPoint från diagramserie. |
| [getDataPointLevels()](#getDataPointLevels--) | Returnerar behållare för datapunktsnivåer. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returnerar en automatisk färg för datapunkt baserat på seriens index, datapunktsindex, egenskapen ParentSeriesGroup.IsColorVaried och diagramstil. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Anger att datapunkten ska invertera sina färger om värdet är negativt. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Anger att datapunkten ska invertera sina färger om värdet är negativt. |
| [getCachedValue()](#getCachedValue--) | Hämtar det cachade värdet för en diagramdatapunkt. |
| [getCachedXValue()](#getCachedXValue--) | Hämtar det cachade X-värdet för en diagramdatapunkt. |
| [getCachedYValue()](#getCachedYValue--) | Hämtar det cachade Y-värdet för en diagramdatapunkt. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Hämtar den cachade bubbeltstorleken för en diagramdatapunkt. |
| [getActualX()](#getActualX--) | Anger den faktiska x-positionen (vänster) för diagramelementet relativt diagrammets övre vänstra hörn. |
| [getActualY()](#getActualY--) | Anger det faktiska övre läget för diagramelementet relativt diagrammets övre vänstra hörn. |
| [getActualWidth()](#getActualWidth--) | Anger den faktiska bredden på diagramelementet. |
| [getActualHeight()](#getActualHeight--) | Anger den faktiska höjden på diagramelementet. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Skrivskyddad [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Returnerar:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Returnerar storleksvärdet för diagramdatapunkten. Används med Treemap- och Sunburst-diagram. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Returnerar färgvärdet för diagramdatapunkten. Används med kartdiagram. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Representerar seriernas felstaplarvärden i fall av anpassad värdetyp. Skrivskyddad [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Returnerar:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Skrivskyddad [IDataLabel](../../com.aspose.slides/idatalabel).

**Returnerar:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Anger att bubblorna har en 3D-effekt tillämpad på dem. Läs/skriv boolean.

**Returnerar:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Anger att bubblorna har en 3D-effekt tillämpad på dem. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Anger hur mycket datapunkten ska flyttas från mitten av pajen. Läs/skriv int.

**Returnerar:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Anger hur mycket datapunkten ska flyttas från mitten av pajen. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representerar formateringsegenskaperna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Representerar formateringsegenskaperna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Anger en datamarkör. Skrivskyddad [IMarker](../../com.aspose.slides/imarker).

**Returnerar:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Sätter datapunkt som total. Tillämpas endast för Waterfall-serietyp.

**Returnerar:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Sätter datapunkt som total. Tillämpas endast för Waterfall-serietyp.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Egenskaper för motsvarande legendpost för diagramtyper från följande lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

Tar bort DataPoint från diagramserie.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Returnerar behållare för datapunktsnivåer. Tillämpas för Treeamp- och Sunburst-serier. Indexering av datapunktsnivåer är nollbaserad.

**Returnerar:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Returnerar:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Returnerar en automatisk färg för datapunkt baserat på seriens index, datapunktsindex, egenskapen ParentSeriesGroup.IsColorVaried och diagramstil. Denna färg används som standard om FillType är lika med NotDefined.

**Returnerar:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Anger att datapunkten ska invertera sina färger om värdet är negativt. Läs/skriv boolean.

**Returnerar:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Anger att datapunkten ska invertera sina färger om värdet är negativt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Hämtar det cachade värdet för en diagramdatapunkt. Skrivskyddad [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Skriv ut alla cachade värden för diagramserien.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Hämtar det cachade X-värdet för en diagramdatapunkt. Skrivskyddad [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Skriv ut alla cachade X värden för diagramserien.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

Hämtar det cachade Y-värdet för en diagramdatapunkt. Skrivskyddad [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Skriv ut alla cachade Y-värden för diagramserien.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Hämtar den cachade bubbeltstorleken för en diagramdatapunkt. Skrivskyddad [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Skriv ut alla cachade bubbeltstorleksvärden för diagramserien.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Anger den faktiska x-positionen (vänster) för diagramelementet relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Anger det faktiska övre läget för diagramelementet relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Anger den faktiska bredden på diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Anger den faktiska höjden på diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. Läs float.

**Returnerar:**
float