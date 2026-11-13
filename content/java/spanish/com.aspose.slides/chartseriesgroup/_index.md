---
title: ChartSeriesGroup
second_title: Referencia API de Aspose.Slides para Java
description: Representa un grupo de series.
type: docs
url: /es/com.aspose.slides/chartseriesgroup/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Representa un grupo de series.

--------------------

1) Consulte el resumen y las observaciones de la clase ChartSeriesGroupCollection y del enum CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de series que son comunes a cada serie del grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Devuelve un tipo de este grupo de series. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica si la serie de este grupo se representa en el eje secundario. |
| [getSeries()](#getSeries--) | Devuelve una colección de series. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getUpDownBars()](#getUpDownBars--) | Proporciona acceso a las barras arriba/abajo de un gráfico de línea o de acciones. |
| [getGapWidth()](#getGapWidth--) | Obtiene o establece el espacio entre los grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. |
| [setGapWidth(int value)](#setGapWidth-int-) | Obtiene o establece el espacio entre los grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. |
| [getGapDepth()](#getGapDepth--) | Obtiene o establece la distancia entre series de datos en un gráfico 3D, como un porcentaje del ancho del marcador. |
| [setGapDepth(int value)](#setGapDepth-int-) | Obtiene o establece la distancia entre series de datos en un gráfico 3D, como un porcentaje del ancho del marcador. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtiene o establece el ángulo de la primera porción de un gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtiene o establece el ángulo de la primera porción de un gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 0 y 90 % del tamaño del área de trazado). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 0 y 90 % del tamaño del área de trazado). |
| [getOverlap()](#getOverlap--) | Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica el tamaño de la segunda porción o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Especifica el tamaño de la segunda porción o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica un valor que se utilizará para determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Especifica un valor que se utilizará para determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica cómo determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Especifica cómo determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de datos en la serie tiene un color diferente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Especifica que cada marcador de datos en la serie tiene un color diferente. |
| [hasSeriesLines()](#hasSeriesLines--) | Verdadero si el gráfico tiene líneas de serie. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Verdadero si el gráfico tiene líneas de serie. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Especifica el formato HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | La información de división personalizada para un gráfico de pastel-de-pastel o barra-de-pastel con división personalizada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Devuelve el gráfico padre. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación padre de un FillFormat. |
### getType() {#getType--}
```
public final int getType()
```


Devuelve un tipo de este grupo de series. Solo lectura [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Devuelve:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```


Indica si la serie de este grupo se representa en el eje secundario. Solo lectura boolean.

**Devuelve:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```


Devuelve una colección de series. Solo lectura [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Devuelve:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```


Proporciona acceso a las barras arriba/abajo de un gráfico de línea o de acciones. Solo lectura [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Devuelve:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


Obtiene o establece el espacio entre los grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. El valor debe estar entre 0 y 500. Lectura/escritura int.

--------------------

Esta propiedad se aplica a series de los siguientes tipos: subtipos Bar (ver también el método [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), subtipos Column (ver también el método [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Devuelve:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```


Obtiene o establece el espacio entre los grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. El valor debe estar entre 0 y 500. Lectura/escritura int.

--------------------

Esta propiedad se aplica a series de los siguientes tipos: subtipos Bar (ver también el método [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), subtipos Column (ver también el método [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


Obtiene o establece la distancia entre series de datos en un gráfico 3D, como un porcentaje del ancho del marcador. El valor debe estar entre 0 y 500. Lectura/escritura int.

--------------------

Esta propiedad se aplica a series de los siguientes tipos: subtipos de barra y columna 3D (ver también el método [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Devuelve:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```


Obtiene o establece la distancia entre series de datos en un gráfico 3D, como un porcentaje del ancho del marcador. El valor debe estar entre 0 y 500. Lectura/escritura int.

--------------------

Esta propiedad se aplica a series de los siguientes tipos: subtipos de barra y columna 3D (ver también el método [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


Obtiene o establece el ángulo de la primera porción de un gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura int.

**Devuelve:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```


Obtiene o establece el ángulo de la primera porción de un gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 0 y 90 % del tamaño del área de trazado). Lectura/escritura byte.

**Devuelve:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```


Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 0 y 90 % del tamaño del área de trazado). Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). - -100 %: Espaciado máximo (las barras están completamente separadas). - 0 %: Las barras se colocan una al lado de la otra sin superposición ni espaciado. - 100 %: Superposición máxima (las barras se superponen completamente). Esta propiedad es Lectura/escritura byte.

--------------------

> ```
> El siguiente ejemplo muestra cómo establecer la superposición para un grupo de series de gráfico 
>   y renderizar el gráfico resultante en un formulario:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Establecer superposición al 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```


Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). - -100 %: Espaciado máximo (las barras están completamente separadas). - 0 %: Las barras se colocan una al lado de la otra sin superposición ni espaciado. - 100 %: Superposición máxima (las barras se superponen completamente). Esta propiedad es Lectura/escritura byte.

--------------------

> ```
> El siguiente ejemplo muestra cómo establecer la superposición para un grupo de series de gráfico 
>   y renderizar el gráfico resultante en un formulario:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Establecer superposición al 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


Especifica el tamaño de la segunda porción o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). Lectura/escritura int.

**Devuelve:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```


Especifica el tamaño de la segunda porción o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura/escritura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Devuelve:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```


Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura/escritura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


Especifica un valor que se utilizará para determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Se usa junto con la propiedad PieSplitBy. Lectura/escritura double.

**Devuelve:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```


Especifica un valor que se utilizará para determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Se usa junto con la propiedad PieSplitBy. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


Especifica cómo determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Lectura/escritura [PieSplitType](../../com.aspose.slides/piesplittype).

**Devuelve:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```


Especifica cómo determinar qué puntos de datos están en la segunda porción o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Lectura/escritura [PieSplitType](../../com.aspose.slides/piesplittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```


Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura boolean.

**Devuelve:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```


Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escritura boolean.

**Devuelve:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```


Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```


Especifica el formato HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose.

**Devuelve:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). Lectura/escritura int.

**Devuelve:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```


Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


La información de división personalizada para un gráfico de pastel-de-pastel o barra-de-pastel con división personalizada. Contiene puntos de datos que se dibujarán en la segunda porción o barra. Solo lectura [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Devuelve:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
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