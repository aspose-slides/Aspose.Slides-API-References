---
title: ChartDataPoint
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un punto dati della serie.
type: docs
url: /it/com.aspose.slides/chartdatapoint/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Rappresenta un punto dati della serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Restituisce il valore di dimensione del punto dati del grafico. |
| [getColorValue()](#getColorValue--) | Restituisce il valore di colore del punto dati del grafico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Specifica che le bolle hanno un effetto 3-D applicato. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifica che le bolle hanno un effetto 3-D applicato. |
| [getExplosion()](#getExplosion--) | Specifica la quantità con cui il punto dati deve essere spostato dal centro della torta. |
| [setExplosion(int value)](#setExplosion-int-) | Specifica la quantità con cui il punto dati deve essere spostato dal centro della torta. |
| [getFormat()](#getFormat--) | Rappresenta le proprietà di formattazione. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta le proprietà di formattazione. |
| [getMarker()](#getMarker--) | Specifica un marcatore dati. |
| [getSetAsTotal()](#getSetAsTotal--) | Imposta il punto dati come totale. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Imposta il punto dati come totale. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Proprietà della voce della legenda corrispondente nel caso di tipo di grafico da questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Rimuove DataPoint dalla serie del grafico. |
| [getDataPointLevels()](#getDataPointLevels--) | Restituisce il contenitore dei livelli del punto dati. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Restituisce un colore automatico del punto dati basato sull'indice della serie, indice del punto dati, proprietà ParentSeriesGroup.IsColorVaried e lo stile del grafico. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifica che il punto dati deve invertire i suoi colori se il valore è negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifica che il punto dati deve invertire i suoi colori se il valore è negativo. |
| [getCachedValue()](#getCachedValue--) | Ottiene il valore memorizzato nella cache di un punto dati del grafico. |
| [getCachedXValue()](#getCachedXValue--) | Ottiene il valore X memorizzato nella cache di un punto dati del grafico. |
| [getCachedYValue()](#getCachedYValue--) | Ottiene il valore Y memorizzato nella cache di un punto dati del grafico. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Ottiene la dimensione della bolla memorizzata nella cache di un punto dati del grafico. |
| [getActualX()](#getActualX--) | Specifica la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualY()](#getActualY--) | Specifica il vertice reale dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualWidth()](#getActualWidth--) | Specifica la larghezza reale dell'elemento del grafico. |
| [getActualHeight()](#getActualHeight--) | Specifica l'altezza reale dell'elemento del grafico. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Solo lettura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Restituisce:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Restituisce il valore di dimensione del punto dati del grafico. Utilizzato con i grafici Treemap e Sunburst. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Restituisce il valore di colore del punto dati del grafico. Utilizzato con i grafici Map. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Custom. Solo lettura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Restituisce:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Solo lettura [IDataLabel](../../com.aspose.slides/idatalabel).

**Restituisce:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Specifică che le bolle hanno un effetto 3-D applicato. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Specifică che le bolle hanno un effetto 3-D applicato. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Specifică la quantità con cui il punto dati deve essere spostato dal centro della torta. Lettura/scrittura int.

**Restituisce:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Specifică la quantità con cui il punto dati deve essere spostato dal centro della torta. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Rappresenta le proprietà di formattazione. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Rappresenta le proprietà di formattazione. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Specifică un marcatore dati. Solo lettura [IMarker](../../com.aspose.slides/imarker).

**Restituisce:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall.

**Restituisce:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Proprietà della voce della legenda corrispondente nel caso di tipo di grafico da questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

Rimuove DataPoint dalla serie del grafico.
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Restituisce il contenitore dei livelli del punto dati. Applicato per le serie Treeamp e Sunburst. L'indicizzazione dei livelli dei punti dati parte da zero.

**Restituisce:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

**Restituisce:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Restituisce un colore automatico del punto dati basato sull'indice della serie, indice del punto dati, proprietà ParentSeriesGroup.IsColorVaried e lo stile del grafico. Questo colore è usato per impostazione predefinita se FillType è uguale a NotDefined.

**Restituisce:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Specifică che il punto dati deve invertire i suoi colori se il valore è negativo. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Specifică che il punto dati deve invertire i suoi colori se il valore è negativo. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Ottiene il valore memorizzato nella cache di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori memorizzati nella cache della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Ottiene il valore X memorizzato nella cache di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori X memorizzati nella cache della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

Ottiene il valore Y memorizzato nella cache di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori Y memorizzati nella cache della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Ottiene la dimensione della bolla memorizzata nella cache di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori della dimensione della bolla memorizzati nella cache della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specifică la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura float.

**Restituisce:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specifică il vertice reale dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura float.

**Restituisce:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specifică la larghezza reale dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura float.

**Restituisce:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specifică l'altezza reale dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura float.

**Restituisce:**
float