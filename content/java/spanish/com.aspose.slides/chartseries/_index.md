---
title: ChartSeries
second_title: Referencia de API de Aspose.Slides para Java
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
| [getChart()](#getChart--) | Devuelve el gráfico principal. |
| [getExplosion()](#getExplosion--) | La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. |
| [setExplosion(int value)](#setExplosion-int-) | La distancia de una porción de pastel abierta desde el centro del gráfico de pastel se expresa como un porcentaje del diámetro del pastel. |
| [getSmooth()](#getSmooth--) | Representa el suavizado de curvas. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representa el suavizado de curvas. |
| [getName()](#getName--) | Devuelve el nombre de la serie. |
| [getDataPoints()](#getDataPoints--) | Devuelve la colección de puntos de datos de esta serie. |
| [getType()](#getType--) | Devuelve un tipo de esta serie. |
| [setType(int value)](#setType-int-) | Devuelve un tipo de esta serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica si esta serie se representa en el eje secundario. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indica si esta serie se representa en el eje secundario. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Devuelve el formato de una serie. |
| [getOrder()](#getOrder--) | Devuelve el orden de una serie. |
| [setOrder(int value)](#setOrder-int-) | Devuelve el orden de una serie. |
| [getLabels()](#getLabels--) | Devuelve las Labels de una serie. |
| [getTrendLines()](#getTrendLines--) | Colección de series trend lines. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representa ErrorBars de la serie con dirección X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representa ErrorBars de la serie con dirección Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa la entrada de leyenda relacionada con esta serie solo de lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
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
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que la serie de barra, columna o burbuja debe invertir sus colores si el valor es negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que la serie de barra, columna o burbuja debe invertir sus colores si el valor es negativo. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Especifica invertir el color sólido para la serie. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Devuelve un color automático de la serie basado en el índice de la serie y el estilo del gráfico. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representa puntos internos. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representa puntos internos. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representa puntos atípicos. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representa puntos atípicos. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representa marcadores de media. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representa marcadores de media. |
| [getShowMeanLine()](#getShowMeanLine--) | Representa la línea de media. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representa la línea de media. |
| [getQuartileMethod()](#getQuartileMethod--) | Representa el método de cuartiles. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representa el método de cuartiles. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representa líneas de conexión. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representa líneas de conexión. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representa el diseño de las etiquetas de categoría padre. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representa el diseño de las etiquetas de categoría padre. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina si el gráfico de líneas o de acciones tiene barras de subida/bajada. |
| [getGapWidth()](#getGapWidth--) | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. |
| [getGapDepth()](#getGapDepth--) | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Especifica el ángulo de la primera porción de pastel o dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre el 10% y el 90% del tamaño del área de trazado). |
| [getOverlap()](#getOverlap--) | Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel-anidado o barra-anidado, como un porcentaje del tamaño del primer pastel (puede estar entre el 5% y el 200%). |
| [hasSeriesLines()](#hasSeriesLines--) | Determina si hay líneas de serie para esta serie y series relacionadas. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica cómo se representan los valores de tamaño de burbujas en el gráfico de burbujas. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-anidado. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-anidado. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | La información de división personalizada para un gráfico de pastel-anidado o barra-anidado con una división personalizada. |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de datos en la serie tiene un color diferente. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0% y 300% del tamaño predeterminado). |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un FillFormat. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo de lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el gráfico principal. Solo de lectura [IChart](../../com.aspose.slides/ichart).

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

Representa el suavizado de curvas. Verdadero si el suavizado de curvas está activado para el gráfico de líneas o de dispersión. Se aplica solo a gráficos de líneas y de dispersión conectados por líneas. Lectura/escritura boolean.

**Devuelve:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Representa el suavizado de curvas. Verdadero si el suavizado de curvas está activado para el gráfico de líneas o de dispersión. Se aplica solo a gráficos de líneas y de dispersión conectados por líneas. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Devuelve el nombre de la serie. Solo de lectura [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Devuelve:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Devuelve la colección de puntos de datos de esta serie. Solo de lectura [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Devuelve:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Devuelve un tipo de esta serie. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Devuelve:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Devuelve un tipo de esta serie. Lectura/escritura [ChartType](../../com.aspose.slides/charttype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indica si esta serie se representa en el eje secundario. Lectura/escritura boolean.

**Devuelve:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Indica si esta serie se representa en el eje secundario. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Solo de lectura [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Devuelve:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Devuelve el formato de una serie. Solo de lectura [IFormat](../../com.aspose.slides/iformat).

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

Devuelve las Labels de una serie. Solo de lectura [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Devuelve:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Colección de series trend lines. Solo de lectura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines están disponibles (no nulos) para series de datos en gráficos de área, barra, columna, línea, acciones, xy (dispersión) y burbujas 2-D sin apilar. No están disponibles para series de datos en cualquier tipo de gráfico que sea apilado o 3-D. Tampoco están disponibles para gráficos de radar, pastel, superficie o dona.

**Devuelve:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Representa ErrorBars de la serie con dirección X. Solo de lectura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars con dirección X están disponibles para series de tipo área, barra, dispersión y burbuja. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados use la colección DataPoints para especificar el valor (con la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Devuelve:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Representa ErrorBars de la serie con dirección Y. Solo de lectura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars con dirección Y están disponibles para series de tipo área, barra, línea, dispersión y burbuja. Para cualquier otro tipo de gráfico esta propiedad devuelve null (incluidos los gráficos 3D). En caso de valores personalizados use la colección DataPoints para especificar el valor (con la propiedad ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Devuelve:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representa la entrada de leyenda relacionada con esta serie Solo de lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Marker. Solo de lectura [IMarker](../../com.aspose.slides/imarker).

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

Especifica que la serie de barra, columna o burbuja debe invertir sus colores si el valor es negativo. Lectura/escritura boolean.

**Devuelve:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Especifica que la serie de barra, columna o burbuja debe invertir sus colores si el valor es negativo. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Especifica el color sólido invertido para la serie. Para aplicar la configuración de color, establezca el formato de la serie FillType a FillType.Solid. Lectura/escritura [ColorFormat](../../com.aspose.slides/colorformat).

**Devuelve:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Devuelve un color automático de la serie basado en el índice de la serie y el estilo del gráfico. Este color se usa por defecto si FillType equals NotDefined.

**Devuelve:**  
java.awt.Color - El objeto java.awt.Color.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Representa los puntos internos. True si los puntos internos se muestran en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Representa los puntos internos. True si los puntos internos se muestran en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Representa los puntos atípicos. True si los puntos atípicos se muestran en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Representa los puntos atípicos. True si los puntos atípicos se muestran en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Representa los marcadores de media. True si los marcadores de media se muestran en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Representa los marcadores de media. True si los marcadores de media se muestran en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Representa la línea de media. True si la línea de media se muestra en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Representa la línea de media. True si la línea de media se muestra en el gráfico BoxAndWhisker. Se aplica solo a los gráficos BoxAndWhisker. Lectura/escritura boolean.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Representa el método de cuartil. Se aplica solo a los gráficos BoxAndWhisker.

**Devuelve:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Representa el método de cuartil. Se aplica solo a los gráficos BoxAndWhisker.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Representa las líneas de conector. Se aplica solo a los gráficos Waterfall.

**Devuelve:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Representa las líneas de conector. Se aplica solo a los gráficos Waterfall.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Representa el diseño de las etiquetas de categoría padre. Se aplica solo a los gráficos Treemap.

**Devuelve:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Representa el diseño de las etiquetas de categoría padre. Se aplica solo a los gráficos Treemap.

**Parámetros:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Determina si el gráfico Line o Stock tiene barras de subida/bajada. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.UpDownBars.HasUpDownBars de lectura/escritura para cambiar el valor. Use la propiedad ParentSeriesGroup.UpDownBars para formatear las barras de subida/bajada. Sólo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Devuelve:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.GapWidth de lectura/escritura para cambiar el valor. Sólo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.GapWidth.

**Devuelve:**  
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.GapDepth de lectura/escritura para cambiar el valor. Sólo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.GapDepth.

**Devuelve:**  
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Especifica el ángulo del primer segmento de un gráfico circular o de dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.FirstSliceAngle de lectura/escritura para cambiar el valor. Sólo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.FirstSliceAngle.

**Devuelve:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Especifica el tamaño del agujero en un gráfico de dona (puede estar entre 10 y 90 por ciento del tamaño del área de trazado). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.DoughnutHoleSize de lectura/escritura para cambiar el valor. Sólo lectura byte.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.DoughnutHoleSize.

**Devuelve:**  
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre. Es una proyección de la propiedad correspondiente en el grupo de series padre, por lo que esta propiedad es solo lectura. Para cambiar el valor, use la propiedad ParentSeriesGroup.Overlap de lectura/escritura. Sólo lectura byte.

--------------------

Overlap especifica el grado de superposición o separación entre barras y columnas como porcentaje de su ancho: -100 %: separación máxima (barras completamente separadas). 0 %: barras colocadas lado a lado sin superposición ni separación. 100 %: superposición máxima (barras se superponen completamente). Esta es una proyección de la propiedad ParentSeriesGroup.Overlap.

**Devuelve:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Especifica el tamaño del segundo segmento o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.SecondPieSize de lectura/escritura para cambiar el valor. Sólo lectura int.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.SecondPieSize.

**Devuelve:**  
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Determina si existen líneas de serie para esta serie y series afines. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.HasSeriesLines de lectura/escritura para cambiar el valor. Use la propiedad ParentSeriesGroup.SeriesLinesFormat para formatear las líneas de serie. Sólo lectura boolean.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.HasSeriesLines.

**Devuelve:**  
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.BubbleSizeRepresentation de lectura/escritura para cambiar el valor.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.BubbleSizeRepresentation.

**Devuelve:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Especifica un valor que se usará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Se usa conjuntamente con la propiedad PieSplitBy. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.PieSplitPosition de lectura/escritura para cambiar el valor. Sólo lectura double.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitPosition.

**Devuelve:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Por lo tanto, esta propiedad es solo lectura. Use la propiedad ParentSeriesGroup para acceder al grupo de series padre. Use la propiedad ParentSeriesGroup.PieSplitBy de lectura/escritura para cambiar el valor. Sólo lectura [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitBy. 2) Si el valor de la propiedad es PieSplitType.Custom, puede definir información de división personalizada con la propiedad ParentSeriesGroup.PieSplitCustomPoints.

**Devuelve:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

La información de división personalizada para un gráfico de pastel-de-pastel o barra-de-pastel con una división personalizada. Contiene los puntos de datos que se dibujarán en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre: es la proyección de la propiedad correspondiente del grupo. Sólo lectura [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.PieSplitCustomPoints.

**Devuelve:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Especifica que cada marcador de datos en la serie tiene un color diferente. Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre - esta es la proyección de la propiedad de grupo correspondiente. Y por lo tanto esta propiedad es de solo lectura. Utilice la propiedad ParentSeriesGroup para acceder al grupo de series padre. Utilice la propiedad ParentSeriesGroup.IsColorVaried de lectura/escritura para cambiar el valor. Booleano de solo lectura.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.IsColorVaried.

**Devuelve:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). Esta es la propiedad no solo de esta serie sino de todas las series del grupo de series padre - esta es la proyección de la propiedad de grupo correspondiente. Y por lo tanto esta propiedad es de solo lectura. Utilice la propiedad ParentSeriesGroup para acceder al grupo de series padre. Utilice la propiedad ParentSeriesGroup.BubbleSizeScale de lectura/escritura para cambiar el valor.

--------------------

Esta es la proyección de la propiedad ParentSeriesGroup.BubbleSizeScale.

**Devuelve:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva padre de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación padre de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)