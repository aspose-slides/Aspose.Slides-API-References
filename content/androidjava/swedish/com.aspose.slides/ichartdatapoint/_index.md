---
title: IChartDataPoint
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar serie-datapunkt.
type: docs
url: /sv/com.aspose.slides/ichartdatapoint/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Representerar serie-datapunkt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXValue()](#getXValue--) | Returnerar x-värdet för diagramdatapunkten. |
| [getYValue()](#getYValue--) | Returnerar y-värdet för diagramdatapunkten. |
| [getBubbleSize()](#getBubbleSize--) | Returnerar bubbels storlek för diagramdatapunkten. |
| [getValue()](#getValue--) | Returnerar värdet för diagramdatapunkten. |
| [getSizeValue()](#getSizeValue--) | Returnerar storleksvärdet för diagramdatapunkten. |
| [getColorValue()](#getColorValue--) | Returnerar färgvärdet för diagramdatapunkten. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representerar seriernas felstapelsvärden vid anpassad (Custom) värdetyp. |
| [getLabel()](#getLabel--) | Representerar etiketten för diagramdatapunkten. |
| [isBubble3D()](#isBubble3D--) | Anger att bubblorna har en 3-D-effekt tillämpad. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Anger att bubblorna har en 3-D-effekt tillämpad. |
| [getExplosion()](#getExplosion--) | Anger hur mycket datapunkten ska flyttas från mitten av pajdiagrammet. |
| [setExplosion(int value)](#setExplosion-int-) | Anger hur mycket datapunkten ska flyttas från mitten av pajdiagrammet. |
| [getFormat()](#getFormat--) | Representerar formateringsegenskaperna. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representerar formateringsegenskaperna. |
| [getMarker()](#getMarker--) | Anger en datamarkör. |
| [remove()](#remove--) | Tar bort DataPoint från diagramserien. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returnerar en automatisk färg för datapunkten baserat på serieindex, datapunktindex, ParentSeriesGroup.IsColorVaried-egenskapen och diagramstilen. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Egenskaper för motsvarande legendpost vid diagramtyp från denna lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Ställer in datapunkten som total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Ställer in datapunkten som total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Anger att datapunkten ska invertera sina färger om värdet är negativt. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Anger att datapunkten ska invertera sina färger om värdet är negativt. |
| [getDataPointLevels()](#getDataPointLevels--) | Returnerar behållare för datapunktsnivåer. |
| [getIndex()](#getIndex--) | Bestämmer vilken av förälderns barnsamling denna datapunkt gäller för. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Returnerar x-värdet för diagramdatapunkten. Skrivskyddad [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Returnerar:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Returnerar y-värdet för diagramdatapunkten. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Returnerar bubbels storlek för diagramdatapunkten. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Returnerar värdet för diagramdatapunkten. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Returnerar storleksvärdet för diagramdatapunkten. Används med Treemap- och Sunburst-diagram. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Returnerar färgvärdet för diagramdatapunkten. Används med kartdiagram. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Representerar seriernas felstapelsvärden vid anpassad (Custom) värdetyp. Skrivskyddad [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Returnerar:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Representerar etiketten för diagramdatapunkten. Skrivskyddad [IDataLabel](../../com.aspose.slides/idatalabel).

**Returnerar:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Anger att bubblorna har en 3-D-effekt tillämpad. Läs/skriv boolesk.

**Returnerar:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Anger att bubblorna har en 3-D-effekt tillämpad. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Anger hur mycket datapunkten ska flyttas från mitten av pajdiagrammet. Läs/skriv int.

**Returnerar:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Anger hur mycket datapunkten ska flyttas från mitten av pajdiagrammet. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representerar formateringsegenskaperna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representerar formateringsegenskaperna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Anger en datamarkör. Skrivskyddad [IMarker](../../com.aspose.slides/imarker).

**Returnerar:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Tar bort DataPoint från diagramserien.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Returnerar en automatisk färg för datapunkten baserat på serieindex, datapunktindex, ParentSeriesGroup.IsColorVaried-egenskapen och diagramstilen. Denna färg används som standard om FillType är lika med NotDefined.

**Returnerar:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Egenskaper för motsvarande legendpost vid diagramtyp från denna lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Ställer in datapunkten som total. Gäller endast för Waterfall-serietyp.

**Returnerar:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Ställer in datapunkten som total. Gäller endast för Waterfall-serietyp.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Anger att datapunkten ska invertera sina färger om värdet är negativt. Läs/skriv boolesk.

**Returnerar:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Anger att datapunkten ska invertera sina färger om värdet är negativt. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Returnerar behållare för datapunktsnivåer. Används för Treeamp- och Sunburst-serier. Indexering av datapunktsnivåer är nollbaserad.

**Returnerar:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bestämmer vilken av förälderns barnsamling denna datapunkt gäller för. Läs long.

**Returnerar:**
long