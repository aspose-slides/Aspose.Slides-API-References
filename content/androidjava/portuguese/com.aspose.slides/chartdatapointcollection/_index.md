---
title: ChartDataPointCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa a coleção de um ponto de dados de série.
type: docs
url: /pt/com.aspose.slides/chartdatapointcollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Representa a coleção de um ponto de dados de série.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o ponto de dados da série pelo índice (seu número de série nesta coleção). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Retorna o índice (número de série) do ponto de dados nesta coleção. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade XValue dos pontos de dados. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade XValue dos pontos de dados. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade YValue dos pontos de dados. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade YValue dos pontos de dados. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade BubbleSize dos pontos de dados. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade BubbleSize dos pontos de dados. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade Value dos pontos de dados. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade Value dos pontos de dados. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Especifica os tipos de valores na lista de propriedades ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Se a coleção já contém um ponto de dados com o índice index, então retorna esse ponto de dados. |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copia para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Cria o novo ponto de dados e o adiciona ao final da coleção. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Remove o valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice fornecido. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Retorna o ponto de dados da série por índice (seu número de série nesta coleção).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Retorna o índice (número de série) do ponto de dados nesta coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Retorna:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade XValue dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.XValue.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retorna:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade XValue dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.XValue.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade YValue dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.YValue.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retorna:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade YValue dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.YValue.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade BubbleSize dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.BubbleSize.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retorna:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade BubbleSize dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.BubbleSize.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade Value dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.Value.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Retorna:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está ativa no objeto da propriedade Value dos pontos de dados. Em outras palavras, especifica o tipo de valor da propriedade ChartDataPoint.Value.Data. Leitura/Escrita [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Especifica os tipos de valores na lista de propriedades ChartDataPoint.ErrorBarsCustomValues. Somente leitura [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Retorna:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Se a coleção já contém um ponto de dados com o índice index, então retorna esse ponto de dados. Se a coleção não contém um ponto de dados com o índice index==N (quando o número de pontos de dados nesta coleção é menor ou igual a N), então adiciona pontos de dados deficientes e retorna o último (que tem o índice solicitado). Por exemplo, os índices da coleção são {0, 1, 2} e o índice solicitado é 5. Então o método adiciona pontos de dados deficientes: {0, 1, 2, 3, 4, 5}. E retorna o ponto de dados com índice 5.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | long | Índice. |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Retorna o ponto de dados com o índice solicitado.

### size() {#size--}
```
public final int size()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Copia para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array para copiar. |
| arrayIndex | int | Índice para iniciar a cópia. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Um java.util.Iterator para toda a coleção.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Stock (veja também o método [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados. |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Stock (veja também o método [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados. |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Line (veja também o método [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados. |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Line (veja também o método [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados. |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Scatter (veja também o método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Scatter (veja também o método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | double | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Scatter (veja também o método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | java.lang.String | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Scatter (veja também o método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Scatter (veja também o método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | double | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Scatter (veja também o método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | java.lang.String | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Radar (veja também o método [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Radar (veja também o método [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Column ou Bar (veja também os métodos [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) e [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Column ou Bar (veja também os métodos [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) e [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Area (veja também o método [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Area (veja também o método [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Pie (veja também o método [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Pie (veja também o método [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Doughnut (veja também o método [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Doughnut (veja também o método [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | double | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | java.lang.String | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | double | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | java.lang.String | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |
| bubbleSize | double | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | double | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |
| bubbleSize | double | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | java.lang.String | XValue do ponto de dados |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue do ponto de dados |
| bubbleSize | double | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |
| bubbleSize | double | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | double | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |
| bubbleSize | double | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Bubble (veja também o método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xValue | java.lang.String | XValue do ponto de dados |
| yValue | double | YValue do ponto de dados |
| bubbleSize | double | BubbleSize do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Surface (veja também o método [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType é um dos subtipos Surface (veja também o método [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chart type é Sunburst.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public  



```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chart type é Treemap.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chart type é BoxAndWhisker.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chart type é Waterfall.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chart type é Histogram.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chart type é Funnel.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chart type é Map.

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


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue do ponto de dados |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Novo ponto de dados.

### clear() {#clear--}
```
public final void clear()
```

Remove todos os elementos da coleção.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Remove o valor especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | O valor. |

### removeAt(int index) {#removeAt-int-}
```
public



```

Remove o elemento no índice fornecido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do ponto de dados a remover. |