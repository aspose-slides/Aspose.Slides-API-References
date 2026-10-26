---
title: Axis
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
url: /es/com.aspose.slides/axis/
---
**Herencia:**  
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Encapsula el objeto que representa el eje de un gráfico.

## Métodos

| Método | Descripción |
| --- | --- |
| [getChart()](#getChart--) | Devuelve el gráfico principal. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Representa si el eje de valores cruza el eje de categorías entre categorías. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Representa si el eje de valores cruza el eje de categorías entre categorías. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Especifica el tipo del eje de categorías. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Especifica el tipo del eje de categorías. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Establece la propiedad IAxis.CategoryAxisType con un valor determinado automáticamente en función de los datos del eje. |
| [getCrossAt()](#getCrossAt--) | Representa el punto del eje donde el eje perpendicular lo cruza. |
| [setCrossAt(float value)](#setCrossAt-float-) | Representa el punto del eje donde el eje perpendicular lo cruza. |
| [getDisplayUnit()](#getDisplayUnit--) | Especifica el valor de escala de las unidades de visualización para el eje de valores. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Especifica el valor de escala de las unidades de visualización para el eje de valores. |
| [getActualMaxValue()](#getActualMaxValue--) | Especifica el valor máximo real en el eje. |
| [getActualMinValue()](#getActualMinValue--) | Especifica el valor mínimo real en el eje. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Especifica la unidad principal real del eje. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Especifica la unidad secundaria real del eje. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Especifica la escala de la unidad principal real del eje. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Especifica la escala de la unidad secundaria real del eje. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indica si el valor máximo se asigna automáticamente. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indica si el valor máximo se asigna automáticamente. |
| [getMaxValue()](#getMaxValue--) | Representa el valor máximo en el eje de valores. |
| [setMaxValue(double value)](#setMaxValue-double-) | Representa el valor máximo en el eje de valores. |
| [getMinorUnit()](#getMinorUnit--) | Representa las unidades secundarias para el eje de fecha o de valores. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Representa las unidades secundarias para el eje de fecha o de valores. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indica si la unidad secundaria del eje se asigna automáticamente. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indica si la unidad secundaria del eje se asigna automáticamente. |
| [getMajorUnit()](#getMajorUnit--) | Representa las unidades principales para el eje de fecha o de valores. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Representa las unidades principales para el eje de fecha o de valores. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indica si la unidad principal del eje se asigna automáticamente. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indica si la unidad principal del eje se asigna automáticamente. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indica si el valor mínimo se asigna automáticamente. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indica si el valor mínimo se asigna automáticamente. |
| [getMinValue()](#getMinValue--) | Representa el valor mínimo en el eje de valores. |
| [setMinValue(double value)](#setMinValue-double-) | Representa el valor mínimo en el eje de valores. |
| [isLogarithmic()](#isLogarithmic--) | Representa si el tipo de escala del eje de valores es logarítmico o no. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Representa si el tipo de escala del eje de valores es logarítmico o no. |
| [getLogBase()](#getLogBase--) | Representa la base logarítmica. |
| [setLogBase(double value)](#setLogBase-double-) | Representa la base logarítmica. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Representa si MS PowerPoint traza los puntos de datos de último a primero. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Representa si MS PowerPoint traza los puntos de datos de último a primero. |
| [isVisible()](#isVisible--) | Representa si el eje es visible. |
| [setVisible(boolean value)](#setVisible-boolean-) | Representa si el eje es visible. |
| [getMajorTickMark()](#getMajorTickMark--) | Representa el tipo de marca de graduación principal para el eje especificado. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Representa el tipo de marca de graduación principal para el eje especificado. |
| [getMinorTickMark()](#getMinorTickMark--) | Representa el tipo de marca de graduación secundaria para el eje especificado. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Representa el tipo de marca de graduación secundaria para el eje especificado. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Representa la escala de la unidad principal para el eje de fecha. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Representa la escala de la unidad principal para el eje de fecha. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Representa la escala de la unidad principal para el eje de fecha. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Representa la escala de la unidad principal para el eje de fecha. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Especifica la unidad de tiempo más pequeña representada en el eje de fecha. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Especifica la unidad de tiempo más pequeña representada en el eje de fecha. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representa el formato de las líneas de cuadrícula secundarias en un eje de gráfico. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representa el formato de las líneas de cuadrícula principales en un eje de gráfico. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Para ocultar la línea de cuadrícula secundaria, establezca MinorGridLinesFormat.Line.FillFormat.FillType a FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Para ocultar la línea de cuadrícula principal, establezca MajorGridLinesFormat.Line.FillFormat.FillType a FillType.NoFill. |
| [getFormat()](#getFormat--) | Representa el formato del eje. |
| [getTextFormat()](#getTextFormat--) | Representa el formato del texto. |
| [getTitle()](#getTitle--) | Obtiene el título del eje. |
| [getCrossType()](#getCrossType--) | Representa el CrossType en el eje especificado donde el otro eje lo cruza. |
| [setCrossType(int value)](#setCrossType-int-) | Representa el CrossType en el eje especificado donde el otro eje lo cruza. |
| [getPosition()](#getPosition--) | Representa la posición del eje. |
| [setPosition(int value)](#setPosition-int-) | Representa la posición del eje. |
| [hasTitle()](#hasTitle--) | Determina si un eje tiene un título visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina si un eje tiene un título visible. |
| [getNumberFormat()](#getNumberFormat--) | Representa la cadena de formato para las etiquetas del eje. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa la cadena de formato para las etiquetas del eje. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indica si el formato está vinculado a datos de origen. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indica si el formato está vinculado a datos de origen. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representa el ángulo de rotación de las etiquetas de graduación. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representa el ángulo de rotación de las etiquetas de graduación. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Especifica el valor de espaciado automático de las etiquetas de graduación. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Especifica el valor de espaciado automático de las etiquetas de graduación. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Especifica el valor de espaciado automático de las marcas de graduación. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Especifica el valor de espaciado automático de las marcas de graduación. |
| [getLabelOffset()](#getLabelOffset--) | Especifica la distancia de las etiquetas respecto al eje. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Especifica la distancia de las etiquetas respecto al eje. |
| [getAggregationType()](#getAggregationType--) | Representa el tipo de agregación del eje de categorías (agrupación). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representa el tipo de agregación del eje de categorías (agrupación). |
| [getBinWidth()](#getBinWidth--) | Especifica el ancho de bin cuando la propiedad AggregationType está configurada a AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Especifica el ancho de bin cuando la propiedad AggregationType está configurada a AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Especifica el número de bins cuando la propiedad AggregationType está configurada a AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Especifica el número de bins cuando la propiedad AggregationType está configurada a AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Especifica si se aplica un bin de desbordamiento. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Especifica si se aplica un bin de desbordamiento. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Especifica el valor automático del bin de desbordamiento. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Especifica el valor automático del bin de desbordamiento. |
| [getOverflowBin()](#getOverflowBin--) | Especifica el valor personalizado del bin de desbordamiento. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Especifica el valor personalizado del bin de desbordamiento. |
| [isUnderflowBin()](#isUnderflowBin--) | Especifica si se aplica un bin de subdesbordamiento. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Especifica si se aplica un bin de subdesbordamiento. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Especifica el valor automático del bin de subdesbordamiento. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Especifica el valor automático del bin de subdesbordamiento. |
| [getUnderflowBin()](#getUnderflowBin--) | Especifica el valor personalizado del bin de subdesbordamiento. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Especifica el valor personalizado del bin de subdesbordamiento. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el gráfico principal. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad se aplica solo a ejes de categorías y no se aplica a gráficos 3-D. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad se aplica solo a ejes de categorías y no se aplica a gráficos 3-D. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Especifica el tipo del eje de categorías. Lectura/escritura [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Devuelve:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Especifica el tipo del eje de categorías. Lectura/escritura [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Establece la propiedad IAxis.CategoryAxisType con un valor determinado automáticamente en función de los datos del eje.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Representa el punto del eje donde el eje perpendicular lo cruza. Lectura/escritura float.

**Devuelve:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Representa el punto del eje donde el eje perpendicular lo cruza. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Especifica el valor de escala de las unidades de visualización para el eje de valores. Lectura/escritura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Devuelve:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Especifica el valor de escala de las unidades de visualización para el eje de valores. Lectura/escritura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Especifica el valor máximo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real.

**Devuelve:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Especifica el valor mínimo real en el eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real.

**Devuelve:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Especifica la unidad principal real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real.

**Devuelve:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Especifica la unidad secundaria real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real.

**Devuelve:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Especifica la escala de la unidad principal real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real.

**Devuelve:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Especifica la escala de la unidad secundaria real del eje. Llame al método IChart.ValidateChartLayout() previamente para obtener el valor real.

**Devuelve:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Indica si el valor máximo se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Indica si el valor máximo se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Representa el valor máximo en el eje de valores. Lectura/escritura double.

**Devuelve:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Representa el valor máximo en el eje de valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Representa las unidades secundarias para el eje de fecha o de valores. Lectura/escritura double.

**Devuelve:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Representa las unidades secundarias para el eje de fecha o de valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Indica si la unidad secundaria del eje se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Indica si la unidad secundaria del eje se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Representa las unidades principales para el eje de fecha o de valores. Lectura/escritura double.

**Devuelve:**  
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Representa las unidades principales para el eje de fecha o de valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Indica si la unidad principal del eje se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Indica si la unidad principal del eje se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Indica si el valor mínimo se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Indica si el valor mínimo se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Representa el valor mínimo en el eje de valores. Lectura/escritura double.

**Devuelve:**  
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Representa el valor mínimo en el eje de valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Representa la base logarítmica. El valor predeterminado es 10. Lectura/escritura double.

**Devuelve:**  
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Representa la base logarítmica. El valor predeterminado es 10. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Representa si MS PowerPoint traza los puntos de datos de último a primero. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Representa si MS PowerPoint traza los puntos de datos de último a primero. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Representa si el eje es visible. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Representa si el eje es visible. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Representa el tipo de marca de graduación principal para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Devuelve:**  
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Representa el tipo de marca de graduación principal para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Representa el tipo de marca de graduación secundaria para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Devuelve:**  
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Representa el tipo de marca de graduación secundaria para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Lectura/escritura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Devuelve:**  
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Lectura/escritura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Representa la escala de la unidad principal para el eje de fecha. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Devuelve:**  
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Representa la escala de la unidad principal para el eje de fecha. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Representa la escala de la unidad principal para el eje de fecha. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Devuelve:**  
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Representa la escala de la unidad principal para el eje de fecha. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Especifica la unidad de tiempo más pequeña representada en el eje de fecha. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Devuelve:**  
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Especifica la unidad de tiempo más pequeña representada en el eje de fecha. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Representa el formato de las líneas de cuadrícula secundarias en un eje de gráfico. Solo lectura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Devuelve:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Representa el formato de las líneas de cuadrícula principales en un eje de gráfico. Solo lectura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Devuelve:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Para ocultar la línea de cuadrícula secundaria, establezca MinorGridLinesFormat.Line.FillFormat.FillType a FillType.NoFill. Solo lectura boolean.

**Devuelve:**  
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Para ocultar la línea de cuadrícula principal, establezca MajorGridLinesFormat.Line.FillFormat.FillType a FillType.NoFill. Solo lectura boolean.

**Devuelve:**  
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Representa el formato del eje. Solo lectura [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Devuelve:**  
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Representa el formato del texto. Solo lectura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Devuelve:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Obtiene el título del eje. Solo lectura [IChartTitle](../../com.aspose.slides/icharttitle).

**Devuelve:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Representa el CrossType en el eje especificado donde el otro eje lo cruza. Lectura/escritura [CrossesType](../../com.aspose.slides/crossestype).

**Devuelve:**  
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Representa el CrossType en el eje especificado donde el otro eje lo cruza. Lectura/escritura [CrossesType](../../com.aspose.slides/crossestype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Representa la posición del eje. Lectura/escritura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Devuelve:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representa la posición del eje. Lectura/escritura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Determina si un eje tiene un título visible. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Determina si un eje tiene un título visible. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Representa la cadena de formato para las etiquetas del eje. Lectura/escritura String.

**Devuelve:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Representa la cadena de formato para las etiquetas del eje. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Indica si el formato está vinculado a datos de origen. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Indica si el formato está vinculado a datos de origen. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Representa el ángulo de rotación de las etiquetas de graduación. Lectura/escritura float.

**Devuelve:**  
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Representa el ángulo de rotación de las etiquetas de graduación. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. Se aplica a ejes de categoría o de series. Lectura/escritura long.

**Devuelve:**  
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. Se aplica a ejes de categoría o de series. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Especifica el valor de espaciado automático de las etiquetas de graduación. Si es false: se usa la propiedad TickLabelSpacing. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Especifica el valor de espaciado automático de las etiquetas de graduación. Si es false: se usa la propiedad TickLabelSpacing. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. Se aplica a ejes de categoría o de series. Lectura/escritura int.

**Devuelve:**  
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. Se aplica a ejes de categoría o de series. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Especifica el valor de espaciado automático de las marcas de graduación. Si es false: se usa la propiedad TickMarksSpacing. Lectura/escritura boolean.

**Devuelve:**  
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Especifica el valor de espaciado automático de las marcas de graduación. Si es false: se usa la propiedad TickMarksSpacing. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Especifica la distancia de las etiquetas respecto al eje. Se aplica a ejes de categoría o de fecha. El valor debe estar entre 0 % y 1000 %. Lectura/escritura int.

**Devuelve:**  
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Especifica la distancia de las etiquetas respecto al eje. Se aplica a ejes de categoría o de fecha. El valor debe estar entre 0 % y 1000 %. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Representa el tipo de agregación del eje de categorías (agrupación). Se aplica a categorías. Solo se usa con series Histogram o HistogramPareto.

**Devuelve:**  
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Representa el tipo de agregación del eje de categorías (agrupación). Se aplica a categorías. Solo se usa con series Histogram o HistogramPareto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Especifica el ancho del bin cuando la propiedad AggregationType está establecida a AxisAggregationType.ByBinWidth. Se aplica a ejes de categorías. Solo se usa con series Histogram o HistogramPareto.

**Devuelve:**  
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Especifica el ancho del bin cuando la propiedad AggregationType está establecida a AxisAggregationType.ByBinWidth. Se aplica a ejes de categorías. Solo se usa con series Histogram o HistogramPareto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Especifica el número de bins cuando la propiedad AggregationType está establecida a AxisAggregationType.ByNumberOfBins. Se aplica a ejes de categorías. Solo se usa con series Histogram o HistogramPareto.

**Devuelve:**  
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Especifica el número de bins cuando la propiedad AggregationType está establecida a AxisAggregationType.ByNumberOfBins. Se aplica a ejes de categorías. Solo se usa con series Histogram o HistogramPareto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Especifica si se aplica un bin de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del bin de desbordamiento.

**Devuelve:**  
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Especifica si se aplica un bin de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del bin de desbordamiento.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Especifica el valor automático del bin de desbordamiento. Si es false: se usa la propiedad OverflowBin.

**Devuelve:**  
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Especifica el valor automático del bin de desbordamiento. Si es false: se usa la propiedad OverflowBin.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Especifica el valor personalizado del bin de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin está configurada a false y la propiedad IsOverflowBin es true.

**Devuelve:**  
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Especifica el valor personalizado del bin de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin está configurada a false y la propiedad IsOverflowBin es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Especifica si se aplica un bin de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del bin de subdesbordamiento.

**Devuelve:**  
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Especifica si se aplica un bin de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del bin de subdesbordamiento.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Especifica el valor automático del bin de subdesbordamiento. Si es false: se usa la propiedad UnderflowBin.

**Devuelve:**  
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Especifica el valor automático del bin de subdesbordamiento. Si es false: se usa la propiedad UnderflowBin.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Especifica el valor personalizado del bin de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin está configurada a false y la propiedad IsUnderflowBin es true.

**Devuelve:**  
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Especifica el valor personalizado del bin de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin está configurada a false y la propiedad IsUnderflowBin es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

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