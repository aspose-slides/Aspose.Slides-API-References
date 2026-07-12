---
title: IChartDataPoint
second_title: Aspose.Slides para Android a través de la referencia de API Java
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

| Método | Descripción |
| --- | --- |
| [getXValue()](#getXValue--) | Devuelve el valor x del punto de datos del gráfico. |
| [getYValue()](#getYValue--) | Devuelve el valor y del punto de datos del gráfico. |
| [getBubbleSize()](#getBubbleSize--) | Devuelve el tamaño de burbuja del punto de datos del gráfico. |
| [getValue()](#getValue--) | Devuelve el valor del punto de datos del gráfico. |
| [getSizeValue()](#getSizeValue--) | Devuelve el valor de tamaño del punto de datos del gráfico. |
| [getColorValue()](#getColorValue--) | Devuelve el valor de color del punto de datos del gráfico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representa los valores de barras de error de la serie en caso de tipo de valor Custom. |
| [getLabel()](#getLabel--) | Representa la etiqueta del punto de datos del gráfico. |
| [isBubble3D()](#isBubble3D--) | Especifica que las burbujas tienen un efecto 3D aplicado. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Especifica que las burbujas tienen un efecto 3D aplicado. |
| [getExplosion()](#getExplosion--) | Especifica la cantidad que el punto de datos debe desplazarse del centro del pastel. |
| [setExplosion(int value)](#setExplosion-int-) | Especifica la cantidad que el punto de datos debe desplazarse del centro del pastel. |
| [getFormat()](#getFormat--) | Representa las propiedades de formato. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa las propiedades de formato. |
| [getMarker()](#getMarker--) | Especifica un marcador de datos. |
| [remove()](#remove--) | Elimina DataPoint de la serie del gráfico. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Devuelve un color automático del punto de datos basado en el índice de la serie, índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propiedades de la entrada de leyenda correspondiente en caso de tipo de gráfico de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Establece el punto de datos como total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Establece el punto de datos como total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que el punto de datos debe invertir sus colores si el valor es negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que el punto de datos debe invertir sus colores si el valor es negativo. |
| [getDataPointLevels()](#getDataPointLevels--) | Devuelve el contenedor de niveles de punto de datos. |
| [getIndex()](#getIndex--) | Determina a cuál de las colecciones hijas del padre se aplica este punto de datos. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Devuelve el valor x del punto de datos del gráfico. Solo lectura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Devuelve:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Devuelve el valor y del punto de datos del gráfico. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Devuelve el tamaño de burbuja del punto de datos del gráfico. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Devuelve el valor del punto de datos del gráfico. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Devuelve el valor de tamaño del punto de datos del gráfico. Se usa con gráficos Treemap y Sunburst. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Devuelve:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Devuelve el valor de color del punto de datos del gráfico. Se usa con gráficos de mapa. Solo lectura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

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


Especifica que las burbujas tienen un efecto 3D aplicado. Boolean de lectura/escritura.

**Devuelve:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Especifica que las burbujas tienen un efecto 3D aplicado. Boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Especifica la cantidad que el punto de datos debe desplazarse del centro del pastel. Int de lectura/escritura.

**Devuelve:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Especifica la cantidad que el punto de datos debe desplazarse del centro del pastel. Int de lectura/escritura.

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
public abstract Integer getAutomaticDataPointColor()
```


Devuelve un color automático del punto de datos basado en el índice de la serie, índice del punto de datos, la propiedad ParentSeriesGroup.IsColorVaried y el estilo del gráfico. Este color se utiliza por defecto si FillType es NotDefined.

**Devuelve:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Propiedades de la entrada de leyenda correspondiente en caso de tipo de gráfico de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Solo lectura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Establece el punto de datos como total. Aplicado solo para el tipo de serie Waterfall.

**Devuelve:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Establece el punto de datos como total. Aplicado solo para el tipo de serie Waterfall.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Especifica que el punto de datos debe invertir sus colores si el valor es negativo. Boolean de lectura/escritura.

**Devuelve:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Especifica que el punto de datos debe invertir sus colores si el valor es negativo. Boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Devuelve el contenedor de niveles de punto de datos. Aplicado para series Treeamp y Sunburst. La indexación de niveles de punto de datos comienza en cero.

**Devuelve:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Determina a cuál de las colecciones hijas del padre se aplica este punto de datos. Long de lectura.

**Devuelve:**
long