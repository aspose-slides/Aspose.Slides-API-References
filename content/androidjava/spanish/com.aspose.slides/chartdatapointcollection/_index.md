---
title: ChartDataPointCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una colección de puntos de datos de una serie.
type: docs
url: /es/com.aspose.slides/chartdatapointcollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Representa una colección de puntos de datos de una serie.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el punto de datos de la serie por índice (su número de serie en esta colección). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Devuelve el índice (número de serie) del punto de datos en esta colección. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad XValue de los puntos de datos. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad XValue de los puntos de datos. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad YValue de los puntos de datos. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad YValue de los puntos de datos. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad BubbleSize de los puntos de datos. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad BubbleSize de los puntos de datos. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad Value de los puntos de datos. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad Value de los puntos de datos. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Especifica los tipos de valores en la lista de propiedades ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Si la colección ya contiene un punto de datos con el índice index, devuelve ese punto de datos. |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copia al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Crea un nuevo punto de datos y lo agrega al final de la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Elimina el valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Devuelve el punto de datos de la serie por índice (su número de serie en esta colección).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Devuelve el índice (número de serie) del punto de datos en esta colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Devuelve:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad XValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.XValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad XValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.XValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad YValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.YValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad YValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.YValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad BubbleSize de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.BubbleSize.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad BubbleSize de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.BubbleSize.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad Value de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.Value.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está activa en el objeto de la propiedad Value de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.Value.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Especifica los tipos de valores en la lista de propiedades ChartDataPoint.ErrorBarsCustomValues. Solo lectura [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Devuelve:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Si la colección ya contiene un punto de datos con el índice index, devuelve ese punto de datos. Si la colección no contiene un punto de datos con índice index==N (cuando el número de puntos de datos en esta colección es menor o igual a N), agrega los puntos de datos faltantes y devuelve el último (que tiene el índice solicitado). Por ejemplo, los índices de la colección son \{0, 1, 2\}, y el índice solicitado es 5. Entonces el método agrega los puntos faltantes: \{0, 1, 2, 3, 4, 5\}. Y devuelve el punto de datos con índice 5.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | long | Índice. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Devuelve el punto de datos con el índice solicitado.

### size() {#size--}
```
public final int size()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Copia al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array al que copiar. |
| arrayIndex | int | Índice desde el cual comenzar a copiar. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura boolean.

**Devuelve:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Un java.util.Iterator para toda la colección.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Stock (ver también el método [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Stock (ver también el método [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Line (ver también el método [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Line (ver también el método [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parámetros::
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | double | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | double | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | double | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Radar (ver también el método [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Radar (ver también el método [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Column o Bar (ver también los métodos [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) y [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Column o Bar (ver también los métodos [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) y [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Area (ver también el método [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Area (ver también el método [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Pie (ver también el método [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Pie (ver también el método [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Doughnut (ver también el método [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Doughnut (ver también el método [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | double | YValue del punto de datos |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | double | YValue del punto de datos |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | double | YValue del punto de datos |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |
| bubbleSize | double | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |
| bubbleSize | double | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |
| bubbleSize | double | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | double | YValue del punto de datos |
| bubbleSize | double | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | double | YValue del punto de datos |
| bubbleSize | double | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | double | YValue del punto de datos |
| bubbleSize | double | BubbleSize del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Surface (ver también el método [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Surface (ver también el método [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Sunburst.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Treemap.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es BoxAndWhisker.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Waterfall.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public I? ...?
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Histogram.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Funnel.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Map.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los elementos de la colección.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | El valor. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice dado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del punto de datos a eliminar. |