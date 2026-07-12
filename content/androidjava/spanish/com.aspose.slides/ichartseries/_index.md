---
title: IChartSeries
second_title: Referencia de API de Aspose.Slides para Android a través de Java
description: Representa una serie de gráfico.
type: docs
url: /es/com.aspose.slides/ichartseries/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Representa una serie de gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getExplosion()](#getExplosion--) | La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. |
| [setExplosion(int value)](#setExplosion-int-) | La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. |
| [getSmooth()](#getSmooth--) | Representa el suavizado de curvas. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representa el suavizado de curvas. |
| [getMarker()](#getMarker--) | Devuelve el marcador de la serie. |
| [getBar3DShape()](#getBar3DShape--) | Especifica la forma de una serie de un gráfico de barras 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Especifica la forma de una serie de un gráfico de barras 3-D. |
| [getName()](#getName--) | Devuelve el nombre de la serie. |
| [getDataPoints()](#getDataPoints--) | Devuelve la colección de puntos de datos de esta serie. |
| [getType()](#getType--) | Devuelve un tipo de esta serie. |
| [setType(int value)](#setType-int-) | Devuelve un tipo de esta serie. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Devuelve el grupo de series padre. |
| [getFormat()](#getFormat--) | Devuelve el formato de una serie. |
| [getOrder()](#getOrder--) | Devuelve el orden de una serie. |
| [setOrder(int value)](#setOrder-int-) | Devuelve el orden de una serie. |
| [getLabels()](#getLabels--) | Devuelve las Etiquetas de una serie. |
| [getTrendLines()](#getTrendLines--) | Colección de líneas de tendencia de la serie Solo lectura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representa las barras de error de la serie con dirección X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representa las barras de error de la serie con dirección Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica si esta serie se grafica en el segundo eje de valores. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indica si esta serie se grafica en el segundo eje de valores. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Devuelve o establece el formato numérico para los valores de la serie. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Devuelve o establece el formato numérico para los valores de la serie. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Devuelve o establece el formato numérico para los valores x de la serie. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Devuelve o establece el formato numérico para los valores x de la serie. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Devuelve o establece el formato numérico para los valores y de la serie. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Devuelve o establece el formato numérico para los valores y de la serie. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Devuelve o establece el formato numérico para los tamaños de burbuja de la serie. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Devuelve o establece el formato numérico para los tamaños de burbuja de la serie. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que la serie de barras, columnas o burbujas invertirá sus colores si el valor es negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que la serie de barras, columnas o burbujas invertirá sus colores si el valor es negativo. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Especifica invertir el color sólido para la serie. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa la entrada de leyenda relacionada con esta serie Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Devuelve un color automático de la serie basado en el índice de la serie y el estilo del gráfico. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representa puntos internos. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representa puntos internos. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representa puntos atípicos. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representa puntos atípicos. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representa marcadores de media. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representa marcadores de media. |
| [getShowMeanLine()](#getShowMeanLine--) | Representa marcadores de media. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representa marcadores de media. |
| [getQuartileMethod()](#getQuartileMethod--) | Representa el método cuartil. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representa el método cuartil. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representa líneas de conector. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representa líneas de conector. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representa el diseño de las etiquetas de categoría padre. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representa el diseño de las etiquetas de categoría padre. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). |
| [hasUpDownBars()](#hasUpDownBars--) | Determina si el gráfico de línea o de cotizaciones tiene barras de subida/bajada. |
| [getGapWidth()](#getGapWidth--) | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. |
| [getGapDepth()](#getGapDepth--) | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de datos en la serie tiene un color diferente. |
| [hasSeriesLines()](#hasSeriesLines--) | Determina si hay líneas de serie para esta serie y series relacionadas. |
| [getOverlap()](#getOverlap--) | Especifica cuánto se superponen las barras y columnas en gráficos 2D, como un porcentaje (de -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel dentro de pastel o barra dentro de pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel dentro de pastel o barra dentro de pastel. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel dentro de pastel o barra dentro de pastel. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 por ciento del tamaño del área de trazado). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Especifica el ángulo de la primera porción del pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | La información de división personalizada para un gráfico de pastel dentro de pastel o barra dentro de pastel con una división personalizada. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. Lectura/escritura int.

**Devuelve:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Representa el suavizado de curvas. Verdadero si el suavizado de curvas está activado para el gráfico de líneas o de dispersión. Se aplica solo a gráficos de líneas y de dispersión conectados por líneas. Lectura/escritura boolean.

**Devuelve:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Representa el suavizado de curvas. Verdadero si el suavizado de curvas está activado para el gráfico de líneas o de dispersión. Se aplica solo a gráficos de líneas y de dispersión conectados por líneas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Devuelve el marcador de la serie. Solo lectura [IMarker](../../com.aspose.slides/imarker).

**Devuelve:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Especifica la forma de una serie de un gráfico de barras 3-D. Cambiar el valor de esta propiedad puede provocar el cambio automático del Tipo de la serie. Lectura/escritura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Devuelve:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Especifica la forma de una serie de un gráfico de barras 3-D. Cambiar el valor de esta propiedad puede provocar el cambio automático del Tipo de la serie. Lectura/escritura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Devuelve el nombre de la serie. Solo lectura [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Devuelve:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Devuelve la colección de puntos de datos de esta serie. Solo lectura [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Devuelve:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Devuelve un tipo de esta serie. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Devuelve:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Devuelve un tipo de esta serie. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Devuelve el grupo de series padre. Solo lectura [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Devuelve:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Devuelve el formato de una serie. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Devuelve el orden de una serie. Lectura/escritura int.

**Devuelve:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Devuelve el orden de una serie. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Devuelve las Etiquetas de una serie. Solo lectura [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Devuelve:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Colección de líneas de tendencia de la serie Solo lectura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Devuelve:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Representa las barras de error de la serie con dirección X. Solo lectura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Las barras de error con dirección X están disponibles para series de tipo area, bar, scatter y bubble. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados use la colección DataPoints para especificar el valor (con la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Devuelve:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Representa las barras de error de la serie con dirección Y. Solo lectura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Las barras de error con dirección Y están disponibles para series de tipo area, bar, line, scatter y bubble. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados use la colección DataPoints para especificar el valor (con la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Devuelve:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indica si esta serie se grafica en el segundo eje de valores. Lectura/escritura boolean.

**Devuelve:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Indica si esta serie se grafica en el segundo eje de valores. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Devuelve o establece el formato numérico para los valores de la serie. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Devuelve o establece el formato numérico para los valores de la serie. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Devuelve o establece el formato numérico para los valores x de la serie. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Devuelve o establece el formato numérico para los valores x de la serie. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Devuelve o establece el formato numérico para los valores y de la serie. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Devuelve o establece el formato numérico para los valores y de la serie. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Devuelve o establece el formato numérico para los tamaños de burbuja de la serie. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Devuelve o establece el formato numérico para los tamaños de burbuja de la serie. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Especifica que la serie de barras, columnas o burbujas invertirá sus colores si el valor es negativo. Lectura/escritura boolean.

**Devuelve:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Especifica que la serie de barras, columnas o burbujas invertirá sus colores si el valor es negativo. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Especifica invertir el color sólido para la serie. Para aplicar la configuración de color establezca el FillType del formato de la serie a FillType.Solid. Lectura/escritura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Representa la entrada de leyenda relacionada con esta serie Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Devuelve un color automático de la serie basado en el índice de la serie y el estilo del gráfico. Este color se usa por defecto si FillType es NotDefined.

**Devuelve:**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Representa puntos internos. Verdadero si los puntos internos se muestran en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Representa puntos internos. Verdadero si los puntos internos se muestran en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Representa puntos atípicos. Verdadero si los puntos atípicos se muestran en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Representa puntos atípicos. Verdadero si los puntos atípicos se muestran en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Representa marcadores de media. Verdadero si los marcadores de media se muestran en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Representa marcadores de media. Verdadero si los marcadores de media se muestran en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Representa marcadores de media. Verdadero si la línea de media se muestra en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Representa marcadores de media. Verdadero si la línea de media se muestra en el gráfico BoxAndWhisker. Se aplica solo a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Representa el método cuartil. Se aplica solo a gráficos BoxAndWhisker.

**Devuelve:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Representa el método cuartil. Se aplica solo a gráficos BoxAndWhisker.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Representa líneas de conector. Se aplica solo a gráficos Waterfall.

**Devuelve:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Representa líneas de conector. Se aplica solo a gráficos Waterfall.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Representa el diseño de las etiquetas de categoría padre. Se aplica solo a gráficos Treemap.

**Devuelve:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Representa el diseño de las etiquetas de categoría padre. Se aplica solo a gráficos Treemap.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.BubbleSizeScale lectura/escritura para cambiar el valor.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.BubbleSizeScale.

**Devuelve:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Determina si el gráfico de línea o de cotizaciones tiene barras de subida/bajada. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.UpDownBars.HasUpDownBars lectura/escritura para cambiar el valor. Use la propiedad ParentSeriesGroup.UpDownBars para formatear las barras de subida/bajada. Solo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Devuelve:**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.GapWidth lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.GapWidth.

**Devuelve:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.GapDepth lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.GapDepth.

**Devuelve:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Especifica que cada marcador de datos en la serie tiene un color diferente. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.IsColorVaried lectura/escritura para cambiar el valor. Solo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.IsColorVaried.

**Devuelve:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Determina si hay líneas de serie para esta serie y series relacionadas. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.HasSeriesLines lectura/escritura para cambiar el valor. Use la propiedad ParentSeriesGroup.SeriesLinesFormat para formatear las líneas de serie. Solo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.HasSeriesLines.

**Devuelve:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente y, por lo tanto, es solo lectura. Para cambiar el valor, use la propiedad ParentSeriesGroup.Overlap lectura/escritura. Solo lectura byte.

--------------------

Overlap especifica el grado de superposición o espacio entre barras y columnas como un porcentaje de su ancho: -100%: Espaciado máximo (barras totalmente separadas). 0%: Barras colocadas una al lado de la otra sin superposición ni espacio. 100%: Superposición máxima (barras completamente superpuestas). Esta es una proyección de la propiedad ParentSeriesGroup.Overlap.

**Devuelve:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Especifica el tamaño del segundo pastel o barra de un gráfico de pastel dentro de pastel o barra dentro de pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.SecondPieSize lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.SecondPieSize.

**Devuelve:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel dentro de pastel o barra dentro de pastel. Se usa junto con la propiedad PieSplitBy. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.PieSplitPosition lectura/escritura para cambiar el valor. Solo lectura double.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitPosition.

**Devuelve:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel dentro de pastel o barra dentro de pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.PieSplitBy lectura/escritura para cambiar el valor. Solo lectura [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitBy. 2) Si el valor de la propiedad es PieSplitType.Custom entonces puede definir información de división personalizada con la propiedad ParentSeriesGroup.PieSplitCustomPoints.

**Devuelve:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 por ciento del tamaño del área de trazado). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.DoughnutHoleSize lectura/escritura para cambiar el valor. Solo lectura byte.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.DoughnutHoleSize.

**Devuelve:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Especifica el ángulo de la primera porción del pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.FirstSliceAngle lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.FirstSliceAngle.

**Devuelve:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

La información de división personalizada para un gráfico de pastel dentro de pastel o barra dentro de pastel con una división personalizada. Contiene puntos de datos que se dibujarán en el segundo pastel o barra en un gráfico de pastel dentro de pastel o barra dentro de pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente Solo lectura [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitCustomPoints.

**Devuelve:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre; es una proyección de la propiedad del grupo correspondiente. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.BubbleSizeRepresentation lectura/escritura para cambiar el valor.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.BubbleSizeRepresentation.

**Devuelve:**
int