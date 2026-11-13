---
title: IChartDataPoint
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il punto dati della serie.
type: docs
url: /it/com.aspose.slides/ichartdatapoint/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Rappresenta il punto dati della serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXValue()](#getXValue--) | Ottiene il valore x di un punto dati del grafico. |
| [getYValue()](#getYValue--) | Ottiene il valore y di un punto dati del grafico. |
| [getBubbleSize()](#getBubbleSize--) | Ottiene la dimensione della bolla di un punto dati del grafico. |
| [getValue()](#getValue--) | Ottiene il valore di un punto dati del grafico. |
| [getCachedXValue()](#getCachedXValue--) | Ottiene il valore X memorizzato di un punto dati del grafico. |
| [getCachedYValue()](#getCachedYValue--) | Ottiene il valore Y memorizzato di un punto dati del grafico. |
| [getCachedValue()](#getCachedValue--) | Ottiene il valore memorizzato di un punto dati del grafico. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Ottiene la dimensione della bolla memorizzata di un punto dati del grafico. |
| [getSizeValue()](#getSizeValue--) | Ottiene il valore di dimensione di un punto dati del grafico. |
| [getColorValue()](#getColorValue--) | Ottiene il valore di colore di un punto dati del grafico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Personalizzato. |
| [getLabel()](#getLabel--) | Rappresenta l'etichetta del punto dati del grafico. |
| [isBubble3D()](#isBubble3D--) | Specifica che le bolle hanno un effetto 3-D applicato. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifica che le bolle hanno un effetto 3-D applicato. |
| [getExplosion()](#getExplosion--) | Specifica la quantità di distanza del punto dati dal centro della torta. |
| [setExplosion(int value)](#setExplosion-int-) | Specifica la quantità di distanza del punto dati dal centro della torta. |
| [getFormat()](#getFormat--) | Rappresenta le proprietà di formattazione. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta le proprietà di formattazione. |
| [getMarker()](#getMarker--) | Specifica un marcatore dati. |
| [remove()](#remove--) | Rimuove DataPoint dalla serie del grafico. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Restituisce un colore automatico del punto dati in base all'indice della serie, indice del punto dati, proprietà ParentSeriesGroup.IsColorVaried e allo stile del grafico. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Proprietà della voce di legenda corrispondente nel caso di tipo di grafico da questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Imposta il punto dati come totale. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Imposta il punto dati come totale. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifica che il punto dati deve invertire i suoi colori se il valore è negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifica che il punto dati deve invertire i suoi colori se il valore è negativo. |
| [getDataPointLevels()](#getDataPointLevels--) | Restituisce il contenitore dei livelli del punto dati. |
| [getIndex()](#getIndex--) | Determina a quale collezione di figli del genitore si applica questo punto dati. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Ottiene il valore x di un punto dati del grafico. Solo lettura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Ritorna:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Ottiene il valore y di un punto dati del grafico. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ritorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Ottiene la dimensione della bolla di un punto dati del grafico. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ritorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Ottiene il valore di un punto dati del grafico. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ritorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```


Ottiene il valore X memorizzato di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori X memorizzati della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Ritorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```


Ottiene il valore Y memorizzato di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori Y memorizzati della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Ritorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Ottiene il valore memorizzato di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori memorizzati della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Ritorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```


Ottiene la dimensione della bolla memorizzata di un punto dati del grafico. Solo lettura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Stampa tutti i valori della dimensione della bolla memorizzati della serie del grafico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Ritorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Ottiene il valore di dimensione di un punto dati del grafico. Utilizzato con grafici Treemap e Sunburst. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ritorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Ottiene il valore di colore di un punto dati del grafico. Utilizzato con grafici Map. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Ritorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Personalizzato. Solo lettura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Ritorna:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Rappresenta l'etichetta del punto dati del grafico. Solo lettura [IDataLabel](../../com.aspose.slides/idatalabel).

**Ritorna:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Specifică che le bolle hanno un effetto 3-D applicato. Lettura/scrittura booleano.

**Ritorna:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Specifică che le bolle hanno un effetto 3-D applicato. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Specifică la quantità di distanza del punto dati dal centro della torta. Lettura/scrittura int.

**Ritorna:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Specifică la quantità di distanza del punto dati dal centro della torta. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Rappresenta le proprietà di formattazione. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Ritorna:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Rappresenta le proprietà di formattazione. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


Specifică un marcatore dati. Solo lettura [IMarker](../../com.aspose.slides/imarker).

**Ritorna:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


Rimuove DataPoint dalla serie del grafico.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Restituisce un colore automatico del punto dati basato sull'indice della serie, indice del punto dati, proprietà ParentSeriesGroup.IsColorVaried e lo stile del grafico. Questo colore è usato per impostazione predefinita se FillType è uguale a NotDefined.

**Ritorna:**
java.awt.Color - Colore automatico del punto dati java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Proprietà della voce di legenda corrispondente nel caso di tipo di grafico da questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Ritorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall.

**Ritorna:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Specifică che il punto dati deve invertire i suoi colori se il valore è negativo. Lettura/scrittura booleano.

**Ritorna:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Specifică che il punto dati deve invertire i suoi colori se il valore è negativo. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Restituisce il contenitore dei livelli del punto dati. Applicato per le serie Treeamp e Sunburst. L'indicizzazione dei livelli del punto dati parte da zero.

**Ritorna:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Determina a quale collezione di figli del genitore si applica questo punto dati. Solo lettura long.

**Ritorna:**
long