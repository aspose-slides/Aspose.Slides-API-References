---
title: IChartDataPoint
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un punto dati della serie.
type: docs
url: /it/com.aspose.slides/ichartdatapoint/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Rappresenta un punto dati della serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXValue()](#getXValue--) | Restituisce il valore x del punto dati del grafico. |
| [getYValue()](#getYValue--) | Restituisce il valore y del punto dati del grafico. |
| [getBubbleSize()](#getBubbleSize--) | Restituisce la dimensione della bolla del punto dati del grafico. |
| [getValue()](#getValue--) | Restituisce il valore del punto dati del grafico. |
| [getSizeValue()](#getSizeValue--) | Restituisce il valore di dimensione del punto dati del grafico. |
| [getColorValue()](#getColorValue--) | Restituisce il valore di colore del punto dati del grafico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Personalizzato. |
| [getLabel()](#getLabel--) | Rappresenta l'etichetta del punto dati del grafico. |
| [isBubble3D()](#isBubble3D--) | Specifica che le bolle hanno un effetto 3-D applicato. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifica che le bolle hanno un effetto 3-D applicato. |
| [getExplosion()](#getExplosion--) | Specifica la quantità con cui il punto dati deve essere spostato dal centro della torta. |
| [setExplosion(int value)](#setExplosion-int-) | Specifica la quantità con cui il punto dati deve essere spostato dal centro della torta. |
| [getFormat()](#getFormat--) | Rappresenta le proprietà di formattazione. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta le proprietà di formattazione. |
| [getMarker()](#getMarker--) | Specifica un marcatore dati. |
| [remove()](#remove--) | Rimuove DataPoint dalla serie del grafico. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Restituisce un colore automatico del punto dati basato sull'indice della serie, indice del punto dati, proprietà ParentSeriesGroup.IsColorVaried e sullo stile del grafico. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Proprietà della voce di legenda corrispondente nel caso di tipo di grafico da questa lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
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

Restituisce il valore x del punto dati del grafico. Solo lettura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Restituisce:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Restituisce il valore y del punto dati del grafico. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Restituisce la dimensione della bolla del punto dati del grafico. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Restituisce il valore del punto dati del grafico. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Restituisce il valore di dimensione del punto dati del grafico. Usato con grafici Treemap e Sunburst. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Restituisce il valore di colore del punto dati del grafico. Usato con grafici Map. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Rappresenta i valori delle barre di errore della serie nel caso di tipo di valore Personalizzato. Solo lettura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Restituisce:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Rappresenta l'etichetta del punto dati del grafico. Solo lettura [IDataLabel](../../com.aspose.slides/idatalabel).

**Restituisce:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Specific a che le bolle hanno un effetto 3-D applicato. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Specific a che le bolle hanno un effetto 3-D applicato. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Specific a la quantità con cui il punto dati deve essere spostato dal centro della torta. Lettura/scrittura int.

**Restituisce:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Specific a la quantità con cui il punto dati deve essere spostato dal centro della torta. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Rappresenta le proprietà di formattazione. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
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

Specific a un marcatore dati. Solo lettura [IMarker](../../com.aspose.slides/imarker).

**Restituisce:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Rimuove DataPoint dalla serie del grafico.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Restituisce un colore automatico del punto dati basato sull'indice della serie, indice del punto dati, proprietà ParentSeriesGroup.IsColorVaried e sullo stile del grafico. Questo colore è usato per impostazione predefinita se FillType è uguale a NotDefined.

**Restituisce:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Proprietà della voce di legenda corrispondente nel caso di tipo di grafico da questa lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Imposta il punto dati come totale. Applicato solo per il tipo di serie Waterfall.

**Restituisce:**
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

Specific a che il punto dati deve invertire i suoi colori se il valore è negativo. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Specific a che il punto dati deve invertire i suoi colori se il valore è negativo. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Restituisce il contenitore dei livelli del punto dati. Applicato per le serie Treeamp e Sunburst. L'indicizzazione dei livelli è basata su zero.

**Restituisce:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Determina a quale collezione di figli del genitore si applica questo punto dati. Lettura long.

**Restituisce:**
long