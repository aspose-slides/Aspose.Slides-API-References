---
title: IDataLabelFormat
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa opciones de formato para DataLabel.
type: docs
url: /es/com.aspose.slides/idatalabelformat/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Representa opciones de formato para DataLabel.

## Métodos

| Método | Descripción |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lectura/escritura boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lectura/escritura boolean. |
| [getNumberFormat()](#getNumberFormat--) | Representa la cadena de formato para el objeto DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa la cadena de formato para el objeto DataLabels. |
| [getFormat()](#getFormat--) | Representa el formato de la etiqueta de datos. |
| [getPosition()](#getPosition--) | Representa la posición de la etiqueta de datos. |
| [setPosition(int value)](#setPosition-int-) | Representa la posición de la etiqueta de datos. |
| [getShowLegendKey()](#getShowLegendKey--) | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. |
| [getShowValue()](#getShowValue--) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. |
| [getShowCategoryName()](#getShowCategoryName--) | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. |
| [getShowSeriesName()](#getShowSeriesName--) | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de serie de las etiquetas de datos en un gráfico. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de serie de las etiquetas de datos en un gráfico. |
| [getShowPercentage()](#getShowPercentage--) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. |
| [getSeparator()](#getSeparator--) | Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad IsNumberFormatLinkedToSource para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad IsNumberFormatLinkedToSource para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" hace que todos DataLabels.get_Item(i).isNumberFormatLinkedToSource() sean iguales a val).

**Devuelve:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad IsNumberFormatLinkedToSource para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad IsNumberFormatLinkedToSource para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" hace que todos DataLabels.get_Item(i).isNumberFormatLinkedToSource() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Representa la cadena de formato para el objeto DataLabels. Lectura/escritura String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection. Cuando se establece esta propiedad con un valor, ese valor también se establece en la propiedad NumberFormat para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hace que todos DataLabels.get_Item(i).getNumberFormat() sean iguales a val).

**Devuelve:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Representa la cadena de formato para el objeto DataLabels. Lectura/escritura String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection. Cuando se establece esta propiedad con un valor, ese valor también se establece en la propiedad NumberFormat para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hace que todos DataLabels.get_Item(i).getNumberFormat() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa el formato de la etiqueta de datos. Solo lectura [IFormat](../../com.aspose.slides/iformat).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad representa el formato predeterminado para las nuevas etiquetas de datos en la colección DataLabelCollection.

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Representa la posición de la etiqueta de datos. Lectura/escritura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection. Representa la posición para los objetos DataLabel. Establecer esta propiedad con un valor también establece este valor en la propiedad Position para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setPosition(val)" hace que todos DataLabels.get_Item(i).getPosition() sean iguales a val).

**Devuelve:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Representa la posición de la etiqueta de datos. Lectura/escritura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection. Representa la posición para los objetos DataLabel. Establecer esta propiedad con un valor también establece este valor en la propiedad Position para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setPosition(val)" hace que todos DataLabels.get_Item(i).getPosition() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLegendKey para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" hace que todos DataLabels.get_Item(i).getShowLegendKey() sean iguales a val).

**Devuelve:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLegendKey para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" hace que todos DataLabels.get_Item(i).getShowLegendKey() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de porcentaje. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowValue para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowValue para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" hace que todos DataLabels.get_Item(i).getShowValue() sean iguales a val).

**Devuelve:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de porcentaje. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowValue para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowValue para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" hace que todos DataLabels.get_Item(i).getShowValue() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. Verdadero muestra el nombre de categoría para las etiquetas de datos en un gráfico. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowCategoryName para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" hace que todos DataLabels.get_Item(i).getShowCategoryName() sean iguales a val).

**Devuelve:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. Verdadero muestra el nombre de categoría para las etiquetas de datos en un gráfico. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowCategoryName para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" hace que todos DataLabels.get_Item(i).getShowCategoryName() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de serie de las etiquetas de datos en un gráfico. Verdadero muestra el nombre de la serie. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowSeriesName para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" hace que todos DataLabels.get_Item(i).getShowSeriesName() sean iguales a val).

**Devuelve:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de serie de las etiquetas de datos en un gráfico. Verdadero muestra el nombre de la serie. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowSeriesName para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" hace que todos DataLabels.get_Item(i).getShowSeriesName() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de porcentaje. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowPercentage para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" hace que todos DataLabels.get_Item(i).getShowPercentage() sean iguales a val).

**Devuelve:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de porcentaje. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowPercentage para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" hace que todos DataLabels.get_Item(i).getShowPercentage() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor del tamaño de burbuja. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowBubbleSize para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" hace que todos DataLabels.get_Item(i).getShowBubbleSize() sean iguales a val).

**Devuelve:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor del tamaño de burbuja. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowBubbleSize para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" hace que todos DataLabels.get_Item(i).getShowBubbleSize() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. Verdadero muestra las líneas guía. Falso las oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLeaderLines para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" hace que todos DataLabels.get_Item(i).getShowLeaderLines() sean iguales a val).

**Devuelve:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. Verdadero muestra las líneas guía. Falso las oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLeaderLines para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" hace que todos DataLabels.get_Item(i).getShowLeaderLines() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" hace que todos DataLabels.get_Item(i).getShowLabelAsDataCallout() sean iguales a val).

**Devuelve:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" hace que todos DataLabels.get_Item(i).getShowLabelAsDataCallout() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de la celda. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLabelValueFromCell para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" hace que todos DataLabels.get_Item(i).getShowLabelValueFromCell() sean iguales a val).

**Devuelve:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de la celda. Falso lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLabelValueFromCell para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" hace que todos DataLabels.get_Item(i).getShowLabelValueFromCell() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. Lectura/escritura String.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad Separator para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" hace que todos DataLabels.get_Item(i).getSeparator() sean iguales a val).

**Devuelve:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. Lectura/escritura String.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad Separator para todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" hace que todos DataLabels.get_Item(i).getSeparator() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |