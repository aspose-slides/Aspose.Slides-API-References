---
title: IChartSeriesGroup
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa un grupo de series.
type: docs
url: /es/com.aspose.slides/ichartseriesgroup/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Representa un grupo de series.

--------------------

1) Ver el resumen y los comentarios de la clase ChartSeriesGroupCollection y la enumeración CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de series que son comunes a cada serie del grupo (“propiedades del grupo de series”). Las “propiedades del grupo de series” en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las “propiedades del grupo de series” puede tener una proyección de solo lectura en la clase ChartSeries.

## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Devuelve un tipo de este grupo de series. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica si las series de este grupo se dibujan en el eje secundario. |
| [getSeries()](#getSeries--) | Devuelve una colección de solo lectura de series de gráfico. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getUpDownBars()](#getUpDownBars--) | Proporciona acceso a las barras de subida/bajada de un gráfico Line- o Stock-chart. |
| [getGapWidth()](#getGapWidth--) | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. |
| [setGapWidth(int value)](#setGapWidth-int-) | Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. |
| [getGapDepth()](#getGapDepth--) | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtiene o establece el ángulo de la primera porción del gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtiene o establece el ángulo de la primera porción del gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de datos en la serie tiene un color diferente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Especifica que cada marcador de datos en la serie tiene un color diferente. |
| [hasSeriesLines()](#hasSeriesLines--) | Verdadero si el gráfico tiene líneas de serie. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Verdadero si el gráfico tiene líneas de serie. |
| [getOverlap()](#getOverlap--) | Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica el tamaño del segundo pastel o barra de un gráfico pie-of-pie o bar-of-pie, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Especifica el tamaño del segundo pastel o barra de un gráfico pie-of-pie o bar-of-pie, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | La información de división personalizada para un gráfico pie-of-pie o bar-of-pie con división personalizada. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 % del tamaño del área de trazado). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 % del tamaño del área de trazado). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Especifica el formato de HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. |

### getType() {#getType--}
```
public abstract int getType()
```

Devuelve un tipo de este grupo de series. Solo lectura [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Devuelve:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indica si las series de este grupo se dibujan en el eje secundario. Solo lectura boolean.

**Devuelve:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Devuelve una colección de solo lectura de series de gráfico. Solo lectura [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Devuelve:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Proporciona acceso a las barras de subida/bajada de un gráfico Line- o Stock-chart. Solo lectura [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Devuelve:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Lectura/escritura int.

**Devuelve:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Especifica el espacio entre grupos de barras o columnas, como un porcentaje del ancho de la barra o columna. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escritura int.

**Devuelve:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Devuelve o establece la distancia, como un porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Obtiene o establece el ángulo de la primera porción del gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura int.

**Devuelve:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Obtiene o establece el ángulo de la primera porción del gráfico de pastel o rosquilla, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escritura boolean.

**Devuelve:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). - -100 %: Espaciado máximo (las barras están completamente separadas). - 0 %: Las barras se colocan una al lado de la otra sin superposición ni espacio. - 100 %: Superposición máxima (las barras se superponen completamente). Esta propiedad es Lectura/escritura byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Establecer superposición al 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Especifica cuánto se superponen las barras y columnas en gráficos 2-D, como un porcentaje (de -100 % a 100 %). - -100 %: Espaciado máximo (las barras están completamente separadas). - 0 %: Las barras se colocan una al lado de la otra sin superposición ni espacio. - 100 %: Superposición máxima (las barras se superponen completamente). Esta propiedad es Lectura/escritura byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
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
public abstract int getSecondPieSize()
```

Especifica el tamaño del segundo pastel o barra de un gráfico pie-of-pie o bar-of-pie, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). Lectura/escritura int.

**Devuelve:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Especifica el tamaño del segundo pastel o barra de un gráfico pie-of-pie o bar-of-pie, como un porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 %). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. Se usa junto con la propiedad PieSplitBy. Lectura/escritura double.

**Devuelve:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Especifica un valor que se utilizará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. Se usa junto con la propiedad PieSplitBy. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. Lectura/escritura [PieSplitType](../../com.aspose.slides/piesplittype).

**Devuelve:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico pie-of-pie o bar-of-pie. Lectura/escritura [PieSplitType](../../com.aspose.slides/piesplittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

La información de división personalizada para un gráfico pie-of-pie o bar-of-pie con división personalizada. Contiene los puntos de datos que se dibujarán en el segundo pastel o barra. Solo lectura [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Devuelve:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 % del tamaño del área de trazado). Lectura/escritura byte.

**Devuelve:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Especifica el tamaño del agujero en un gráfico de rosquilla (puede estar entre 10 y 90 % del tamaño del área de trazado). Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). Lectura/escritura int.

**Devuelve:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 % del tamaño predeterminado). Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Especifica el formato de HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose.

**Devuelve:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura/escritura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Devuelve:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura/escritura [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |