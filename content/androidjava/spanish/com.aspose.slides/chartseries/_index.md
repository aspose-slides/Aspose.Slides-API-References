---
title: ChartSeries
second_title: Referencia API de Aspose.Slides para Android vía Java
description: Representa una serie de gráfico.
type: docs
url: /es/com.aspose.slides/chartseries/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Representa una serie de gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Devuelve el gráfico padre. |
| [getExplosion()](#getExplosion--) | La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. |
| [setExplosion(int value)](#setExplosion-int-) | La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. |
| [getSmooth()](#getSmooth--) | Representa el suavizado de curvas. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representa el suavizado de curvas. |
| [getName()](#getName--) | Devuelve el nombre de la serie. |
| [getDataPoints()](#getDataPoints--) | Devuelve la colección de puntos de datos de esta serie. |
| [getType()](#getType--) | Devuelve el tipo de esta serie. |
| [setType(int value)](#setType-int-) | Devuelve el tipo de esta serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica si esta serie se traza en el eje secundario. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indica si esta serie se traza en el eje secundario. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Devuelve el formato de una serie. |
| [getOrder()](#getOrder--) | Devuelve el orden de una serie. |
| [setOrder(int value)](#setOrder-int-) | Devuelve el orden de una serie. |
| [getLabels()](#getLabels--) | Devuelve las Etiquetas de una serie. |
| [getTrendLines()](#getTrendLines--) | Colección de líneas de tendencia de serie. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representa ErrorBars de la serie con dirección X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representa ErrorBars de la serie con dirección Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa la entrada de leyenda relacionada con esta serie Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Especifica la forma de una serie de un gráfico de barras 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Especifica la forma de una serie de un gráfico de barras 3-D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que la serie de barra, columna o burbuja invertirá sus colores si el valor es negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que la serie de barra, columna o burbuja invertirá sus colores si el valor es negativo. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Especifica invertir color sólido para la serie. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Devuelve un color automático de la serie basado en el índice de la serie y el estilo del gráfico. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representa puntos internos. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representa puntos internos. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representa puntos atípicos. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representa puntos atípicos. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representa marcadores de media. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representa marcadores de media. |
| [getShowMeanLine()](#getShowMeanLine--) | Representa línea de media. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representa línea de media. |
| [getQuartileMethod()](#getQuartileMethod--) | Representa método cuartil. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representa método cuartil. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representa líneas de conexión. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representa líneas de conexión. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representa el diseño de las etiquetas de categoría principal. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representa el diseño de las etiquetas de categoría principal. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina si un gráfico de líneas o de acciones tiene barras de arriba/abajo. |
| [getGapWidth()](#getGapWidth--) | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. |
| [getGapDepth()](#getGapDepth--) | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Especifica el ángulo de la primera porción de pastel o dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre el 10% y el 90% del tamaño del área de trazado). |
| [getOverlap()](#getOverlap--) | Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel de pastel o barra de pastel, como un porcentaje del tamaño del primer pastel (puede estar entre el 5% y el 200%). |
| [hasSeriesLines()](#hasSeriesLines--) | Determina si hay líneas de serie para esta serie y series afines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica un valor que se usará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel de pastel o barra de pastel. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel de pastel o barra de pastel. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | La información de división personalizada para un gráfico de pastel de pastel o barra de pastel con una división personalizada. |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de datos en la serie tiene un color diferente. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre el 0% y el 300% del tamaño predeterminado). |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el gráfico padre. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. Lectura/escritura int.

**Devuelve:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Representa el suavizado de curvas. True si el suavizado de curvas está activado para el gráfico de líneas o dispersión. Solo se aplica a gráficos de líneas y dispersión conectados por líneas. Lectura/escritura boolean.

**Devuelve:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Representa el suavizado de curvas. True si el suavizado de curvas está activado para el gráfico de líneas o dispersión. Solo se aplica a gráficos de líneas y dispersión conectados por líneas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Devuelve el nombre de la serie. Solo lectura [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Devuelve:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Devuelve la colección de puntos de datos de esta serie. Solo lectura [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Devuelve:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Devuelve el tipo de esta serie. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Devuelve:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Devuelve el tipo de esta serie. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indica si esta serie se traza en el eje secundario. Lectura/escritura boolean.

**Devuelve:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Indica si esta serie se traza en el eje secundario. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Solo lectura [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Devuelve:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Devuelve el formato de una serie. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Devuelve el orden de una serie. Lectura/escritura int.

**Devuelve:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Devuelve el orden de una serie. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Devuelve las Etiquetas de una serie. Solo lectura [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Devuelve:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Colección de líneas de tendencia de serie. Solo lectura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Las TrendLines están disponibles (no nulas) para series de datos en gráficos de área, barra, columna, línea, acciones, xy (dispersión) y burbuja 2-D no apilados. No están disponibles para series en cualquier tipo de gráfico que sea apilado o 3-D. Tampoco están disponibles para gráficos de radar, pastel, superficie o dona.

**Devuelve:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Representa ErrorBars de la serie con dirección X. Solo lectura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars con dirección X están disponibles para series de tipo área, barra, dispersión y burbuja. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados use la colección DataPoints para especificar el valor (con la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Devuelve:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Representa ErrorBars de la serie con dirección Y. Solo lectura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars con dirección Y están disponibles para series de tipo área, barra, línea, dispersión y burbuja. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados use la colección DataPoints para especificar el valor (con la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Devuelve:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representa la entrada de leyenda relacionada con esta serie Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Solo lectura [IMarker](../../com.aspose.slides/imarker).

**Devuelve:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Especifica la forma de una serie de un gráfico de barras 3-D. Cambiar el valor de esta propiedad puede provocar el cambio automático del Tipo de la serie. Lectura/escritura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Devuelve:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Especifica la forma de una serie de un gráfico de barras 3-D. Cambiar el valor de esta propiedad puede provocar el cambio automático del Tipo de la serie. Lectura/escritura [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Especifica que la serie de barra, columna o burbuja invertirá sus colores si el valor es negativo. Lectura/escritura boolean.

**Devuelve:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Especifica que la serie de barra, columna o burbuja invertirá sus colores si el valor es negativo. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Especifica invertir color sólido para la serie. Para aplicar la configuración de color, establezca el formato de la serie FillType a FillType.Solid. Lectura/escritura [ColorFormat](../../com.aspose.slides/colorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Devuelve un color automático de la serie basado en el índice de la serie y el estilo del gráfico. Este color se usa por defecto si FillType es NotDefined.

**Devuelve:**
java.lang.Integer - El objeto java.lang.Integer.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Representa puntos internos. True si los puntos internos se muestran en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Representa puntos internos. True si los puntos internos se muestran en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Representa puntos atípicos. True si los puntos atípicos se muestran en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Representa puntos atípicos. True si los puntos atípicos se muestran en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Representa marcadores de media. True si los marcadores de media se muestran en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Representa marcadores de media. True si los marcadores de media se muestran en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Representa línea de media. True si la línea de media se muestra en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Representa línea de media. True si la línea de media se muestra en el gráfico BoxAndWhisker. Solo se aplica a gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Representa método cuartil. Solo se aplica a gráficos BoxAndWhisker.

**Devuelve:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Representa método cuartil. Solo se aplica a gráficos BoxAndWhisker.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Representa líneas de conexión. Solo se aplica a gráficos Waterfall.

**Devuelve:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Representa líneas de conexión. Solo se aplica a gráficos Waterfall.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Representa el diseño de las etiquetas de categoría principal. Solo se aplica a gráficos Treemap.

**Devuelve:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Representa el diseño de las etiquetas de categoría principal. Solo se aplica a gráficos Treemap.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Determina si un gráfico de líneas o de acciones tiene barras de arriba/abajo. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.UpDownBars.HasUpDownBars lectura/escritura para cambiar el valor. Use la propiedad ParentSeriesGroup.UpDownBars para formato de barras arriba/abajo. Solo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Devuelve:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.GapWidth lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.GapWidth.

**Devuelve:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.GapDepth lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.GapDepth.

**Devuelve:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Especifica el ángulo de la primera porción de pastel o dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.FirstSliceAngle lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.FirstSliceAngle.

**Devuelve:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Especifica el tamaño del agujero en un gráfico de dona (puede estar entre el 10% y el 90% del tamaño del área de trazado). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.DoughnutHoleSize lectura/escritura para cambiar el valor. Solo lectura byte.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.DoughnutHoleSize.

**Devuelve:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre. Es una proyección de la propiedad correspondiente en el grupo de series padre, por lo que esta propiedad es solo lectura. Para cambiar el valor, use la propiedad ParentSeriesGroup.Overlap lectura/escritura. Solo lectura byte.

--------------------

Overlap especifica el grado de superposición o espacio entre barras y columnas como un porcentaje de su ancho: -100%: Espaciado máximo (barras completamente separadas). 0%: Las barras están una al lado de la otra sin superposición ni espacio. 100%: Superposición máxima (barras completamente solapadas). Esta es una proyección de la propiedad ParentSeriesGroup.Overlap.

**Devuelve:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Especifica el tamaño del segundo pastel o barra de un gráfico de pastel de pastel o barra de pastel, como un porcentaje del tamaño del primer pastel (puede estar entre el 5% y el 200%). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.SecondPieSize lectura/escritura para cambiar el valor. Solo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.SecondPieSize.

**Devuelve:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Determina si hay líneas de serie para esta serie y series afines. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.HasSeriesLines lectura/escritura para cambiar el valor. Use la propiedad ParentSeriesGroup.SeriesLinesFormat para formato de líneas de serie. Solo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.HasSeriesLines.

**Devuelve:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.BubbleSizeRepresentation lectura/escritura para cambiar el valor.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.BubbleSizeRepresentation.

**Devuelve:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Especifica un valor que se usará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel de pastel o barra de pastel. Se usa junto con la propiedad PieSplitBy. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.PieSplitPosition lectura/escritura para cambiar el valor. Solo lectura double.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitPosition.

**Devuelve:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel de pastel o barra de pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.PieSplitBy lectura/escritura para cambiar el valor. Solo lectura [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitBy. 2) Si el valor de la propiedad es PieSplitType.Custom entonces puede definir información de división personalizada con la propiedad ParentSeriesGroup.PieSplitCustomPoints.

**Devuelve:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

La información de división personalizada para un gráfico de pastel de pastel o barra de pastel con una división personalizada. Contiene puntos de datos que se dibujarán en el segundo pastel o barra en un gráfico de pastel de pastel o barra de pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo Solo lectura [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitCustomPoints.

**Devuelve:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Especifica que cada marcador de datos en la serie tiene un color diferente. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.IsColorVaried lectura/escritura para cambiar el valor. Solo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.IsColorVaried.

**Devuelve:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Especifica el factor de escala para el gráfico de burbujas (puede estar entre el 0% y el 300% del tamaño predeterminado). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre – es la proyección de la propiedad correspondiente del grupo. Por lo tanto esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.BubbleSizeScale lectura/escritura para cambiar el valor.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.BubbleSizeScale.

**Devuelve:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva principal de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación principal de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)