---
title: IChartDataPointCollection
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa una colección de un punto de datos de serie.
type: docs
url: /es/com.aspose.slides/ichartdatapointcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Representa una colección de un punto de datos de serie.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el punto de datos de la serie por índice (su número de serie en esta colección). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Devuelve el índice (número de serie en esta colección) del punto de datos en esta colección. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad XValue de los puntos de datos. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad XValue de los puntos de datos. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad YValue de los puntos de datos. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad YValue de los puntos de datos. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad BubbleSize de los puntos de datos. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad BubbleSize de los puntos de datos. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad Value de los puntos de datos. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad Value de los puntos de datos. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Especifica el tipo de valores en la lista de propiedades ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Si la colección ya contiene un punto de datos con el índice index, devuelve este punto de datos. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Crea el nuevo punto de datos y lo agrega al final de la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Elimina el valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice indicado. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
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
public abstract int get_Item(IChartDataPoint pt)
```

Devuelve el índice (número de serie en esta colección) del punto de datos en esta colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Devuelve:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad XValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPointEx.XValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad XValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPointEx.XValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad YValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPointEx.YValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad YValue de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPointEx.YValue.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceForBubbleSizes()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad BubbleSize de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPointEx.BubbleSize.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad BubbleSize de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPointEx.BubbleSize.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad Value de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.Value.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Devuelve:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble está presente en el objeto de la propiedad Value de los puntos de datos. En otras palabras, especifica el tipo de valor de la propiedad ChartDataPoint.Value.Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Especifica el tipo de valores en la lista de propiedades ChartDataPoint.ErrorBarsCustomValues. Solo lectura [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Devuelve:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Si la colección ya contiene un punto de datos con el índice index, devuelve este punto de datos. Si la colección no contiene un punto de datos con index==N (cuando el número de puntos de datos en esta colección es menor o igual a N), agrega los puntos de datos deficientes y devuelve el último (que tiene el índice solicitado). Por ejemplo, los índices de la colección son {0, 1, 2}, y el índice solicitado es 5. Entonces el método agrega puntos deficientes: {0, 1, 2, 3, 4, 5}. Y devuelve el punto de datos con índice 5.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | long | Índice. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Devuelve el punto de datos con el índice solicitado.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Stock (ver también el método ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Stock (ver también el método ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Line (ver también el método ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Line (ver también el método ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue del punto de datos |
| yValue | double | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | double | XValue del punto de datos |
| yValue | double | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Scatter (ver también el método ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xValue | java.lang.String | XValue del punto de datos |
| yValue | double | YValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Radar (ver también el método ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Radar (ver también el método ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Column o Bar (ver también los métodos ChartTypeCharacterizer.IsChartTypeColumn(ChartType) y ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Column o Bar (ver también los métodos ChartTypeCharacterizer.IsChartTypeColumn(ChartType) y ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Area (ver también el método ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Area (ver también el método ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Pie (ver también el método ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Pie (ver también el método ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Doughnut (ver también el método ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Doughnut (ver también el método ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Bubble (ver también el método ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

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
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Surface (ver también el método ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos Surface (ver también el método ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Sunburst.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Waterfall.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es BoxAndWhisker.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```

```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Treemap.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Histogram.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Funnel.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Valor del punto de datos |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Nuevo punto de datos.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Map.

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
public abstract void clear()
```

Elimina todos los elementos de la colección.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | El valor. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice indicado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del punto de datos a eliminar. |
