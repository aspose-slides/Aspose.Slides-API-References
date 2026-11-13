---
title: IChartDataPoint
second_title: Aspose.Slides para Java Referencia de API
description: Representa un punto de datos de la serie.
type: docs
url: /es/com.aspose.slides/ichartdatapoint/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Representa un punto de datos de la serie.

## Métodos

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | Obtiene el valor x de un punto de datos del gráfico. |
| [getYValue()](#getYValue--) | Obtiene el valor y de un punto de datos del gráfico. |
| [getBubbleSize()](#getBubbleSize--) | Obtiene el tamaño de burbuja de un punto de datos del gráfico. |
| [getValue()](#getValue--) | Obtiene el valor de un punto de datos del gráfico. |
| [getCachedXValue()](#getCachedXValue--) | Obtiene el valor X en caché de un punto de datos del gráfico. |
| [getCachedYValue()](#getCachedYValue--) | Obtiene el valor Y en caché de un punto de datos del gráfico. |
| [getCachedValue()](#getCachedValue--) | Obtiene el valor en caché de un punto de datos del gráfico. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Obtiene el tamaño de burbuja en caché de un punto de datos del gráfico. |
| [getSizeValue()](#getSizeValue--) | Obtiene el valor de tamaño de un punto de datos del gráfico. |
| [getColorValue()](#getColorValue--) | Obtiene el valor de color de un punto de datos del gráfico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representa los valores de barras de error de la serie en caso de tipo de valor Custom. |
| [getLabel()](#getLabel--) | Representa la etiqueta del punto de datos del gráfico. |
| [isBubble3D()](#isBubble3D--) | Especifica que las burbujas tienen un efecto 3D aplicado. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Especifica que las burbujas tienen un efecto 3D aplicado. |
| [getExplosion()](#getExplosion--) | Especifica la cantidad que el punto de datos debe moverse desde el centro del gráfico de pastel. |
| [setExplosion(int value)](#setExplosion-int-) | Especifica la cantidad que el punto de datos debe moverse desde el centro del gráfico de pastel. |
| [getFormat()](#getFormat--) | Representa las propiedades de formato. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa las propiedades de formato. |
| [getMarker()](#getMarker--) | Especifica un marcador de datos. |
| [remove()](#remove--) | Elimina DataPoint de la serie del gráfico. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propiedades de la entrada de leyenda correspondiente en caso de tipos de gráfico de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Establece el punto de datos como total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Establece el punto de datos como total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que el punto de datos debe invertir sus colores si el valor es negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que el punto de datos debe invertir sus colores si el valor es negativo. |
| [getDataPointLevels()](#getDataPointLevels--) | Devuelve el contenedor de niveles del punto de datos. |
| [getIndex()](#getIndex--) | Determina a cuál de las colecciones de hijos del padre se aplica este punto de datos. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Obtiene el valor x de un punto de datos del gráfico. Solo lectura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Devuelve:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Obtiene el valor y de un punto de datos del gráfico. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Obtiene el tamaño de burbuja de un punto de datos del gráfico. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Obtiene el valor de un punto de datos del gráfico. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

Obtiene el valor X en caché de un punto de datos del gráfico. Solo lectura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprime todos los valores X en caché de la serie del gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

Obtiene el valor Y en caché de un punto de datos del gráfico. Solo lectura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprime todos los valores Y en caché de la serie del gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Obtiene el valor en caché de un punto de datos del gráfico. Solo lectura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprime todos los valores en caché de la serie del gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

Obtiene el tamaño de burbuja en caché de un punto de datos del gráfico. Solo lectura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprime todos los valores del tamaño de burbuja en caché de la serie del gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Obtiene el valor de tamaño de un punto de datos del gráfico. Se usa con gráficos Treemap y Sunburst. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Obtiene el valor de color de un punto de datos del gráfico. Se usa con gráficos de mapa. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Representa los valores de barras de error de la serie en caso de tipo de valor Custom. Solo lectura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Devuelve:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Representa la etiqueta del punto de datos del gráfico. Solo lectura [IDataLabel](../../com.aspose.slides/idatalabel).

**Devuelve:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Especifica que las burbujas tienen un efecto 3D aplicado. Booleano de lectura/escritura.

**Devuelve:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Especifica que las burbujas tienen un efecto 3D aplicado. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Especifica la cantidad que el punto de datos debe moverse desde el centro del gráfico de pastel. Int de lectura/escritura.

**Devuelve:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Especifica la cantidad que el punto de datos debe moverse desde el centro del gráfico de pastel. Int de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa las propiedades de formato. [IFormat](../../com.aspose.slides/iformat) de lectura/escritura.

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representa las propiedades de formato. [IFormat](../../com.aspose.slides/iformat) de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Especifica un marcador de datos. Solo lectura [IMarker](../../com.aspose.slides/imarker).

**Devuelve:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Elimina DataPoint de la serie del gráfico.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. Este color se usa por defecto si FillType es NotDefined.

**Devuelve:**
java.awt.Color - Color automático del punto de datos java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Propiedades de la entrada de leyenda correspondiente en caso de tipos de gráfico de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Establece el punto de datos como total. Se aplica solo para series de tipo Waterfall.

**Devuelve:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Establece el punto de datos como total. Se aplica solo para series de tipo Waterfall.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Especifica que el punto de datos debe invertir sus colores si el valor es negativo. Booleano de lectura/escritura.

**Devuelve:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Especifica que el punto de datos debe invertir sus colores si el valor es negativo. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Devuelve el contenedor de niveles del punto de datos. Aplicado a series TreeMap y Sunburst. El indexado de los niveles del punto de datos comienza en cero.

**Devuelve:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Determina a cuál de las colecciones de hijos del padre se aplica este punto de datos. Long de solo lectura.

**Devuelve:**
long