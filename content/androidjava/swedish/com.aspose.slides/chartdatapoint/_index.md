---
title: ChartDataPoint
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar seriedatapunkt.
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

Representerar seriedatapunkt.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returnerar storleksvärdet för diagramdatapunkt. |
| [getColorValue()](#getColorValue--) | Returnerar färgvärdet för diagramdatapunkt. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representerar serie felstaplar värden i fall av Custom värdetyp. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Anger att bubblorna har en 3-D-effekt tillämpad på dem. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Anger att bubblorna har en 3-D-effekt tillämpad på dem. |
| [getExplosion()](#getExplosion--) | Anger hur mycket datapunkten ska flyttas från mitten av pajen. |
| [setExplosion(int value)](#setExplosion-int-) | Anger hur mycket datapunkten ska flyttas från mitten av pajen. |
| [getFormat()](#getFormat--) | Representerar formateringsegenskaperna. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representerar formateringsegenskaperna. |
| [getMarker()](#getMarker--) | Anger en datamarkör. |
| [getSetAsTotal()](#getSetAsTotal--) | Ställer in datapunkten som total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ställer in datapunkten som total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Egenskaper för motsvarande legendpost i fall av diagramtyp från denna lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Tar bort DataPoint från diagramserier. |
| [getDataPointLevels()](#getDataPointLevels--) | Returnerar behållare för datapunktsnivåer. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returnerar en automatisk färg för datapunkten baserat på serie-index, datapunkt-index, ParentSeriesGroup.IsColorVaried-egenskapen och diagramstil. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Anger att datapunkten ska invertera sina färger om värdet är negativt. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Anger att datapunkten ska invertera sina färger om värdet är negativt. |
| [getActualX()](#getActualX--) | Anger den faktiska x-positionen (vänster) för diagramelementet relativt diagrammets övre vänstra hörn. |
| [getActualY()](#getActualY--) | Anger den faktiska översta positionen för diagramelementet relativt diagrammets övre vänstra hörn. |
| [getActualWidth()](#getActualWidth--) | Anger den faktiska bredden på diagramelementet. |
| [getActualHeight()](#getActualHeight--) | Anger den faktiska höjden på diagramelementet. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. **Skrivskyddad** [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Returnerar:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. **Skrivskyddad** [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. **Skrivskyddad** [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. **Skrivskyddad** [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Returnerar storleksvärdet för diagramdatapunkt. Används med Treemap- och Sunburst-diagram. **Skrivskyddad** [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Returnerar färgvärdet för diagramdatapunkt. Används med Map-diagram. **Skrivskyddad** [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Representerar serie felstaplar värden i fall av Custom värdetyp. **Skrivskyddad** [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Returnerar:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. **Skrivskyddad** [IDataLabel](../../com.aspose.slides/idatalabel).

**Returnerar:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Anger att bubblorna har en 3-D-effekt tillämpad på dem. **Läs/skriv boolesk**.

**Returnerar:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Anger att bubblorna har en 3-D-effekt tillämpad på dem. **Läs/skriv boolesk**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Anger hur mycket datapunkten ska flyttas från mitten av pajen. **Läs/skriv int**.

**Returnerar:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Anger hur mycket datapunkten ska flyttas från mitten av pajen. **Läs/skriv int**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representerar formateringsegenskaperna. **Läs/skriv** [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Representerar formateringsegenskaperna. **Läs/skriv** [IFormat](../../com.aspose.slides/iformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Anger en datamarkör. **Skrivskyddad** [IMarker](../../com.aspose.slides/imarker).

**Returnerar:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Ställer in datapunkten som total. Tillämplig endast för Waterfall-serietyp.

**Returnerar:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Ställer in datapunkten som total. Tillämplig endast för Waterfall-serietyp.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Egenskaper för motsvarande legendpost i fall av diagramtyp från denna lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. **Skrivskyddad** [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Tar bort DataPoint från diagramserier.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Returnerar behållare för datapunktsnivåer. Tillämplig för Treeamp- och Sunburst-serier. Indexering av datapunktsnivåer är nollbaserad.

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

Returnerar Parent_Immediate-objekt. **Skrivskyddad** IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

Returnerar en automatisk färg för datapunkten baserat på serie-index, datapunkt-index, ParentSeriesGroup.IsColorVaried-egenskapen och diagramstil. Denna färg används som standard om FillType är NotDefined.

**Returnerar:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Anger att datapunkten ska invertera sina färger om värdet är negativt. **Läs/skriv boolesk**.

**Returnerar:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Anger att datapunkten ska invertera sina färger om värdet är negativt. **Läs/skriv boolesk**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Anger den faktiska x-positionen (vänster) för diagramelementet relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. **Läs float**.

**Returnerar:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Anger den faktiska översta positionen för diagramelementet relativt diagrammets övre vänstra hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. **Läs float**.

**Returnerar:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Anger den faktiska bredden på diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. **Läs float**.

**Returnerar:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Anger den faktiska höjden på diagramelementet. Anropa metoden IChart.ValidateChartLayout() innan för att få faktiska värden. **Läs float**.

**Returnerar:**
float