---
title: IAxis
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
url: /es/com.aspose.slides/iaxis/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Encapsula el objeto que representa el eje de un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Representa si el eje de valores cruza el eje de categorías entre categorías. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Representa si el eje de valores cruza el eje de categorías entre categorías. |
| [getCrossAt()](#getCrossAt--) | Representa el punto en el eje donde el eje perpendicular lo cruza. |
| [setCrossAt(float value)](#setCrossAt-float-) | Representa el punto en el eje donde el eje perpendicular lo cruza. |
| [getDisplayUnit()](#getDisplayUnit--) | Especifica el valor de escala de las unidades de visualización para el eje de valores. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Especifica el valor de escala de las unidades de visualización para el eje de valores. |
| [getActualMaxValue()](#getActualMaxValue--) | Especifica el valor máximo real en el eje. |
| [getActualMinValue()](#getActualMinValue--) | Especifica el valor mínimo real en el eje. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Especifica la unidad mayor real del eje. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Especifica la unidad menor real del eje. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Especifica la escala de la unidad mayor real del eje. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Especifica la escala de la unidad menor real del eje. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indica si el valor máximo se asigna automáticamente. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indica si el valor máximo se asigna automáticamente. |
| [getMaxValue()](#getMaxValue--) | Representa el valor máximo en el eje de valores. |
| [setMaxValue(double value)](#setMaxValue-double-) | Representa el valor máximo en el eje de valores. |
| [getMinorUnit()](#getMinorUnit--) | Representa las unidades menores para el eje de fechas o valores. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Representa las unidades menores para el eje de fechas o valores. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indica si la unidad menor del eje se asigna automáticamente. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indica si la unidad menor del eje se asigna automáticamente. |
| [getMajorUnit()](#getMajorUnit--) | Representa las unidades mayores para el eje de fechas o valores. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Representa las unidades mayores para el eje de fechas o valores. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indica si la unidad mayor del eje se asigna automáticamente. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indica si la unidad mayor del eje se asigna automáticamente. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indica si el valor mínimo se asigna automáticamente. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indica si el valor mínimo se asigna automáticamente. |
| [getMinValue()](#getMinValue--) | Representa el valor mínimo en el eje de valores. |
| [setMinValue(double value)](#setMinValue-double-) | Representa el valor mínimo en el eje de valores. |
| [isLogarithmic()](#isLogarithmic--) | Representa si el tipo de escala del eje de valores es logarítmico o no. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Representa si el tipo de escala del eje de valores es logarítmico o no. |
| [getLogBase()](#getLogBase--) | Representa la base logarítmica. |
| [setLogBase(double value)](#setLogBase-double-) | Representa la base logarítmica. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Representa si MS PowerPoint grafica los puntos de datos de último a primero. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Representa si MS PowerPoint grafica los puntos de datos de último a primero. |
| [isVisible()](#isVisible--) | Representa si el eje es visible. |
| [setVisible(boolean value)](#setVisible-boolean-) | Representa si el eje es visible. |
| [getMajorTickMark()](#getMajorTickMark--) | Representa el tipo de marca de graduación mayor para el eje especificado. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Representa el tipo de marca de graduación mayor para el eje especificado. |
| [getMinorTickMark()](#getMinorTickMark--) | Representa el tipo de marca de graduación menor para el eje especificado. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Representa el tipo de marca de graduación menor para el eje especificado. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Representa la escala de la unidad mayor para el eje de fechas. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Representa la escala de la unidad mayor para el eje de fechas. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Representa la escala de la unidad mayor para el eje de fechas. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Representa la escala de la unidad mayor para el eje de fechas. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Especifica la unidad de tiempo más pequeña representada en el eje de fechas. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Especifica la unidad de tiempo más pequeña representada en el eje de fechas. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representa el formato de líneas de cuadrícula menores en un eje de gráfico. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representa el formato de líneas de cuadrícula mayores en un eje de gráfico. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Representa si se mostraron las líneas de cuadrícula menores. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Representa si se mostraron las líneas de cuadrícula mayores. |
| [getFormat()](#getFormat--) | Representa el formato del eje. |
| [getTitle()](#getTitle--) | Obtiene el título del eje. |
| [getCrossType()](#getCrossType--) | Representa el CrossType en el eje especificado donde el otro eje lo cruza. |
| [setCrossType(int value)](#setCrossType-int-) | Representa el CrossType en el eje especificado donde el otro eje lo cruza. |
| [getPosition()](#getPosition--) | Representa la posición del eje. |
| [setPosition(int value)](#setPosition-int-) | Representa la posición del eje. |
| [hasTitle()](#hasTitle--) | Determina si un eje tiene un título visible. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina si un eje tiene un título visible. |
| [getNumberFormat()](#getNumberFormat--) | Representa la cadena de formato para las etiquetas del eje. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa la cadena de formato para las etiquetas del eje. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indica si el formato está enlazado a los datos de origen. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indica si el formato está enlazado a los datos de origen. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representa el ángulo de rotación de las etiquetas de graduación. Lectura/escritura float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representa el ángulo de rotación de las etiquetas de graduación. Lectura/escritura float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Especifica el valor de espaciado automático de etiquetas de graduación. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Especifica el valor de espaciado automático de etiquetas de graduación. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Especifica el valor de espaciado automático de marcas de graduación. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Especifica el valor de espaciado automático de marcas de graduación. |
| [getLabelOffset()](#getLabelOffset--) | Especifica la distancia de las etiquetas respecto al eje. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Especifica la distancia de las etiquetas respecto al eje. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Especifica el tipo del eje de categorías. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Especifica el tipo del eje de categorías. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Establece la propiedad IAxis.CategoryAxisType con un valor determinado automáticamente según los datos del eje. |
| [getAggregationType()](#getAggregationType--) | Representa el tipo de agregación del eje de categorías (agrupación). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representa el tipo de agregación del eje de categorías (agrupación). |
| [getBinWidth()](#getBinWidth--) | Especifica el ancho de cubeta cuando la propiedad AggregationType está establecida en AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Especifica el ancho de cubeta cuando la propiedad AggregationType está establecida en AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Especifica el número de cubetas cuando la propiedad AggregationType está establecida en AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Especifica el número de cubetas cuando la propiedad AggregationType está establecida en AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Especifica si se aplica cubeta de desbordamiento. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Especifica si se aplica cubeta de desbordamiento. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Especifica el valor automático de cubeta de desbordamiento. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Especifica el valor automático de cubeta de desbordamiento. |
| [getOverflowBin()](#getOverflowBin--) | Especifica el valor personalizado de cubeta de desbordamiento. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Especifica el valor personalizado de cubeta de desbordamiento. |
| [isUnderflowBin()](#isUnderflowBin--) | Especifica si se aplica cubeta de subflujo. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Especifica si se aplica cubeta de subflujo. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Especifica el valor automático de cubeta de subflujo. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Especifica el valor automático de cubeta de subflujo. |
| [getUnderflowBin()](#getUnderflowBin--) | Especifica el valor personalizado de cubeta de subflujo. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Especifica el valor personalizado de cubeta de subflujo. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad solo se aplica a ejes de categorías y no a gráficos 3-D. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad solo se aplica a ejes de categorías y no a gráficos 3-D. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Representa el punto en el eje donde el eje perpendicular lo cruza. Lectura/escritura float.

**Devuelve:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Representa el punto en el eje donde el eje perpendicular lo cruza. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Especifica el valor de escala de las unidades de visualización para el eje de valores. Lectura/escritura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Devuelve:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Especifica el valor de escala de las unidades de visualización para el eje de valores. Lectura/escritura [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Especifica el valor máximo real en el eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real.

**Devuelve:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Especifica el valor mínimo real en el eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real.

**Devuelve:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Especifica la unidad mayor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real.

**Devuelve:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Especifica la unidad menor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real.

**Devuelve:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Especifica la escala de la unidad mayor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real.

**Devuelve:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Especifica la escala de la unidad menor real del eje. Llame previamente al método IChart.ValidateChartLayout() para obtener el valor real.

**Devuelve:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indica si el valor máximo se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indica si el valor máximo se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Representa el valor máximo en el eje de valores. Lectura/escritura double.

**Devuelve:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Representa el valor máximo en el eje de valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Representa las unidades menores para el eje de fechas o valores. Lectura/escritura double.

**Devuelve:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Representa las unidades menores para el eje de fechas o valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indica si la unidad menor del eje se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indica si la unidad menor del eje se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Representa las unidades mayores para el eje de fechas o valores. Lectura/escritura double.

**Devuelve:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Representa las unidades mayores para el eje de fechas o valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indica si la unidad mayor del eje se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indica si la unidad mayor del eje se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indica si el valor mínimo se asigna automáticamente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indica si el valor mínimo se asigna automáticamente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Representa el valor mínimo en el eje de valores. Lectura/escritura double.

**Devuelve:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Representa el valor mínimo en el eje de valores. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura/escritura boolean.

**Devuelve:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Representa la base logarítmica. El valor predeterminado es 10. Lectura/escritura double.

**Devuelve:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Representa la base logarítmica. El valor predeterminado es 10. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Representa si MS PowerPoint grafica los puntos de datos de último a primero. Lectura/escritura boolean.

**Devuelve:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Representa si MS PowerPoint grafica los puntos de datos de último a primero. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Representa si el eje es visible. Lectura/escritura boolean.

**Devuelve:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Representa si el eje es visible. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Representa el tipo de marca de graduación mayor para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Devuelve:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Representa el tipo de marca de graduación mayor para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Representa el tipo de marca de graduación menor para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Devuelve:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Representa el tipo de marca de graduación menor para el eje especificado. Lectura/escritura [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Lectura/escritura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Devuelve:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Lectura/escritura [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Representa la escala de la unidad mayor para el eje de fechas. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Devuelve:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Representa la escala de la unidad mayor para el eje de fechas. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Representa la escala de la unidad mayor para el eje de fechas. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Devuelve:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Representa la escala de la unidad mayor para el eje de fechas. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Especifica la unidad de tiempo más pequeña representada en el eje de fechas. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Devuelve:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Especifica la unidad de tiempo más pequeña representada en el eje de fechas. Lectura/escritura [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Representa el formato de líneas de cuadrícula menores en un eje de gráfico. Solo lectura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Devuelve:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Representa el formato de líneas de cuadrícula mayores en un eje de gráfico. Solo lectura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Devuelve:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Representa si se mostraron las líneas de cuadrícula menores. Solo lectura boolean.

**Devuelve:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public int --  ? ? 
```

Representa si se mostraron las líneas de cuadrícula mayores. Solo lectura boolean.

**Devuelve:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Representa el formato del eje. Solo lectura [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Devuelve:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Obtiene el título del eje. Solo lectura [IChartTitle](../../com.aspose.slides/icharttitle).

**Devuelve:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Representa el CrossType en el eje especificado donde el otro eje lo cruza. Lectura/escritura [CrossesType](../../com.aspose.slides/crossestype).

**Devuelve:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Representa el CrossType en el eje especificado donde el otro eje lo cruza. Lectura/escritura [CrossesType](../../com.aspose.slides/crossestype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Representa la posición del eje. Lectura/escritura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Devuelve:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Representa la posición del eje. Lectura/escritura [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Determina si un eje tiene un título visible. Lectura/escritura boolean.

**Devuelve:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Determina si un eje tiene un título visible. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Representa la cadena de formato para las etiquetas del eje. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Representa la cadena de formato para las etiquetas del eje. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indica si el formato está enlazado a los datos de origen. Lectura/escritura boolean.

**Devuelve:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indica si el formato está enlazado a los datos de origen. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Representa el ángulo de rotación de las etiquetas de graduación. Lectura/escritura float.

**Devuelve:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Representa el ángulo de rotación de las etiquetas de graduación. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. Lectura/escritura long.

**Devuelve:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Especifica cuántas etiquetas de graduación se omiten entre las que se dibujan. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Especifica el valor de espaciado automático de etiquetas de graduación. Si es false: se usa la propiedad TickLabelSpacing. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Especifica el valor de espaciado automático de etiquetas de graduación. Si es false: se usa la propiedad TickLabelSpacing. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. Aplicado a ejes de categoría o serie. Lectura/escritura int.

**Devuelve:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. Aplicado a ejes de categoría o serie. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Especifica el valor de espaciado automático de marcas de graduación. Si es false: se usa la propiedad TickMarksSpacing. Lectura/escritura boolean.

**Devuelve:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Especifica el valor de espaciado automático de marcas de graduación. Si es false: se usa la propiedad TickMarksSpacing. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Especifica la distancia de las etiquetas respecto al eje. Aplicado a ejes de categoría o fecha. El valor debe estar entre 0 % y 1000 %. Lectura/escritura int.

**Devuelve:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Especifica la distancia de las etiquetas respecto al eje. Aplicado a ejes de categoría o fecha. El valor debe estar entre 0 % y 1000 %. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Especifica el tipo del eje de categorías. Lectura/escritura [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Devuelve:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Especifica el tipo del eje de categorías. Lectura/escritura [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Establece la propiedad IAxis.CategoryAxisType con un valor determinado automáticamente según los datos del eje.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Representa el tipo de agregación del eje de categorías (agrupación). Aplicado a categoría. Usado solo con series Histogram o HistogramPareto.

**Devuelve:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Representa el tipo de agregación del eje de categorías (agrupación). Aplicado a categoría. Usado solo con series Histogram o HistogramPareto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Especifica el ancho de cubeta cuando la propiedad AggregationType está establecida en AxisAggregationType.ByBinWidth. Aplicado a ejes de categorías. Usado solo con series Histogram o HistogramPareto.

**Devuelve:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Especifica el ancho de cubeta cuando la propiedad AggregationType está establecida en AxisAggregationType.ByBinWidth. Aplicado a ejes de categorías. Usado solo con series Histogram o HistogramPareto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Especifica el número de cubetas cuando la propiedad AggregationType está establecida en AxisAggregationType.ByNumberOfBins. Aplicado a ejes de categorías. Usado solo con series Histogram o HistogramPareto.

**Devuelve:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Especifica el número de cubetas cuando la propiedad AggregationType está establecida en AxisAggregationType.ByNumberOfBins. Aplicado a ejes de categorías. Usado solo con series Histogram o HistogramPareto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Especifica si se aplica cubeta de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor de la cubeta de desbordamiento.

**Devuelve:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Especifica si se aplica cubeta de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor de la cubeta de desbordamiento.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Especifica el valor automático de cubeta de desbordamiento. Si es false: se usa la propiedad OverflowBin.

**Devuelve:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Especifica el valor automático de cubeta de desbordamiento. Si es false: se usa la propiedad OverflowBin.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Especifica el valor personalizado de la cubeta de desbordamiento. Aplicado cuando la propiedad IsAutomaticOverflowBin está establecida en false y IsOverflowBin es true.

**Devuelve:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Especifica el valor personalizado de la cubeta de desbordamiento. Aplicado cuando la propiedad IsAutomaticOverflowBin está establecida en false y IsOverflowBin es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Especifica si se aplica cubeta de subflujo. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor de la cubeta de subflujo.

**Devuelve:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Especifica si se aplica cubeta de subflujo. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor de la cubeta de subflujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Especifica el valor automático de cubeta de subflujo. Si es false: se usa la propiedad UnderflowBin.

**Devuelve:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Especifica el valor automático de cubeta de subflujo. Si es false: se usa la propiedad UnderflowBin.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Especifica el valor personalizado de la cubeta de subflujo. Aplicado cuando la propiedad IsAutomaticUnderflowBin está establecida en false y IsUnderflowBin es true.

**Devuelve:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Especifica el valor personalizado de la cubeta de subflujo. Aplicado cuando la propiedad IsAutomaticUnderflowBin está establecida en false y IsUnderflowBin es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |