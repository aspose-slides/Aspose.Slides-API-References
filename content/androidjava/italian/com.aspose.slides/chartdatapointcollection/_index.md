---
title: ChartDataPointCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta la collezione di un punto dati di una serie.
type: docs
url: /it/com.aspose.slides/chartdatapointcollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Rappresenta una collezione di un punto dati della serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il punto dati della serie per indice (il suo numero di serie in questa collezione). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Restituisce l'indice (numero di serie) del punto dati in questa collezione. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà XValue dei punti dati. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà XValue dei punti dati. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà YValue dei punti dati. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà YValue dei punti dati. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà BubbleSize dei punti dati. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà BubbleSize dei punti dati. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà Value dei punti dati. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà Value dei punti dati. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Specifica i tipi di valori nella lista di proprietà ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Se la collezione contiene già un punto dati con indice index, restituisce quel punto dati. |
| [size()](#size--) | Ottiene il numero di elementi effettivamente contenuti nella collezione. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copia nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce un oggetto di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera collezione. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Crea il nuovo punto dati e lo aggiunge alla fine della collezione. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Rimuove il valore specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice indicato. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Restituisce il punto dati della serie per indice (il suo numero di serie in questa collezione).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Restituisce l'indice (numero di serie) del punto dati in questa collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Restituisce:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà XValue dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.XValue.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Restituisce:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà XValue dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.XValue.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà YValue dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.YValue.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Restituisce:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà YValue dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.YValue.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà BubbleSize dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.BubbleSize.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Restituisce:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà BubbleSize dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.BubbleSize.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà Value dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.Value.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Restituisce:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Specificа se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva nell'oggetto della proprietà Value dei punti dati. In altre parole, specifica il tipo di valore della proprietà ChartDataPoint.Value.Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Specificа i tipi di valori nella lista di proprietà ChartDataPoint.ErrorBarsCustomValues. Solo lettura [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Restituisce:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Se la collezione contiene già un punto dati con indice index, restituisce quel punto dati. Se la collezione non contiene un punto dati con indice index==N (quando il numero di punti dati nella collezione è minore o uguale a N) allora aggiunge i punti dati mancanti e restituisce l'ultimo (che ha l'indice richiesto). Per esempio, gli indici della collezione sono \{0, 1, 2\}, e l'indice richiesto è 5. Il metodo aggiunge i punti dati mancanti: \{0, 1, 2, 3, 4, 5\}. E restituisce il punto dati con indice 5.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | long | Indice. |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Restituisce il punto dati con l'indice richiesto.
### size() {#size--}
```
public final int size()
```

Ottiene il numero di elementi effettivamente contenuti nella collezione. Solo lettura int.

**Restituisce:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Copia nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| arrayIndex | int | Indice a partire dal quale copiare. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce un oggetto di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Restituisce un iteratore Java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un java.util.Iterator per l'intera collezione.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Stock (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati. |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Stock (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati. |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Line (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati. |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Line (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati. |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Scatter (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Scatter (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | double | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Scatter (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Scatter (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto dati |
| yValue | double | YValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Scatter (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | double | XValue del punto dati |
| yValue | double | YValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Scatter (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto dati |
| yValue | double | YValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Radar (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Radar (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Column o Bar (vedi anche i metodi [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) e [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Column o Bar (vedi anche i metodi [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) e [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Area (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Area (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Pie (vedi anche il metodo [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Pie (vedi anche il metodo [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Doughnut (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Doughnut (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | double | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto dati |
| yValue | double | YValue del punto dati |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | double | XValue del punto dati |
| yValue | double | YValue del punto dati |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto dati |
| yValue | double | YValue del punto dati |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |
| bubbleSize | double | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | double | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dati |
| bubbleSize | double | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto dati |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto dato |
| bubbleSize | double | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto dati |
| yValue | double | YValue del punto dati |
| bubbleSize | double | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | double | XValue del punto dati |
| yValue | double | YValue del punto dati |
| bubbleSize | double | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Bubble (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto dati |
| yValue | double | YValue del punto dati |
| bubbleSize | double | BubbleSize del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Surface (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chartType è uno dei sottotipi Surface (vedi anche il metodo [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chart type è Sunburst.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chart type è Treemap.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dato.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chart type è BoxAndWhisker.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dato.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chart type è Waterfall.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dato.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chart type è Histogram.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dato.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chart type è Funnel.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valore del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dato.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Crea il nuovo punto dati e lo aggiunge alla fine della collezione. Applicabile alle serie il cui chart type è Map.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue del punto dati |

**Restituisce:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuovo punto dati.
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla collezione.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Rimuove il valore specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Il valore. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice indicato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un punto dati da rimuovere. |