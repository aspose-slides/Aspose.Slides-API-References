---
title: ChartDataPoint
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un punto de datos de la serie.
type: docs
url: /es/com.aspose.slides/chartdatapoint/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Representa el punto de datos de la serie.
## Métodos

| Método | Descripción |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Devuelve el valor de tamaño del punto de datos del gráfico. |
| [getColorValue()](#getColorValue--) | Devuelve el valor de color del punto de datos del gráfico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representa los valores de barras de error de la serie en caso de tipo de valor Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Especifica que las burbujas tienen un efecto 3-D aplicado. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Especifica que las burbujas tienen un efecto 3-D aplicado. |
| [getExplosion()](#getExplosion--) | Especifica la cantidad que el punto de datos debe desplazarse desde el centro del pastel. |
| [setExplosion(int value)](#setExplosion-int-) | Especifica la cantidad que el punto de datos debe desplazarse desde el centro del pastel. |
| [getFormat()](#getFormat--) | Representa las propiedades de formato. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa las propiedades de formato. |
| [getMarker()](#getMarker--) | Especifica un marcador de datos. |
| [getSetAsTotal()](#getSetAsTotal--) | Establece el punto de datos como total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Establece el punto de datos como total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propiedades de la entrada de leyenda correspondiente en caso de que el tipo de gráfico sea uno de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Elimina DataPoint de la serie del gráfico. |
| [getDataPointLevels()](#getDataPointLevels--) | Devuelve el contenedor de los niveles del punto de datos. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que el punto de datos debe invertir sus colores si el valor es negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que el punto de datos debe invertir sus colores si el valor es negativo. |
| [getActualX()](#getActualX--) | Especifica la ubicación real x (izquierda) del elemento del gráfico respecto a la esquina superior izquierda del gráfico. |
| [getActualY()](#getActualY--) | Especifica la parte superior real del elemento del gráfico respecto a la esquina superior izquierda del gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica el ancho real del elemento del gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica la altura real del elemento del gráfico. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Solo lectura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Devuelve:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Devuelve el valor de tamaño del punto de datos del gráfico. Se usa con gráficos Treemap y Sunburst. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Devuelve el valor de color del punto de datos del gráfico. Se usa con gráficos Map. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Representa los valores de barras de error de la serie en caso de tipo de valor Custom. Solo lectura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Devuelve:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Solo lectura [IDataLabel](../../com.aspose.slides/idatalabel).

**Devuelve:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Especifica que las burbujas tienen un efecto 3-D aplicado. Lectura/escritura boolean.

**Devuelve:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Especifica que las burbujas tienen un efecto 3-D aplicado. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Especifica la cantidad que el punto de datos debe desplazarse desde el centro del pastel. Lectura/escritura int.

**Devuelve:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Especifica la cantidad que el punto de datos debe desplazarse desde el centro del pastel. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Representa las propiedades de formato. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Representa las propiedades de formato. Lectura/escritura [IFormat](../../com.aspose.slides/iformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Especifica un marcador de datos. Solo lectura [IMarker](../../com.aspose.slides/imarker).

**Devuelve:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Establece el punto de datos como total. Se aplica solo para el tipo de serie Waterfall.

**Devuelve:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Establece el punto de datos como total. Se aplica solo para el tipo de serie Waterfall.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Propiedades de la entrada de leyenda correspondiente en caso de que el tipo de gráfico sea uno de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


Elimina DataPoint de la serie del gráfico.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Devuelve el contenedor de los niveles del punto de datos. Se aplica para series Treeamp y Sunburst. La indexación de los niveles es basada en cero.

**Devuelve:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Devuelve:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```


Devuelve un color automático del punto de datos basado en el índice de la serie, el índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. Este color se usa por defecto si FillType equivale a NotDefined.

**Devuelve:**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Especifica que el punto de datos debe invertir sus colores si el valor es negativo. Lectura/escritura boolean.

**Devuelve:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Especifica que el punto de datos debe invertir sus colores si el valor es negativo. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


Especifica la ubicación real x (izquierda) del elemento del gráfico respecto a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Especifica la parte superior real del elemento del gráfico respecto a la esquina superior izquierda del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Especifica el ancho real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Especifica la altura real del elemento del gráfico. Llame al método IChart.ValidateChartLayout() antes para obtener los valores reales. Lectura float.

**Devuelve:**
float