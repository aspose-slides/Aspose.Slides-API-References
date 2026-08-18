---
title: DataLabelFormat
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa opciones de formato para DataLabel.
type: docs
url: /es/com.aspose.slides/datalabelformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Representa opciones de formato para DataLabel.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lectura/escritura booleano. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lectura/escritura booleano. |
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
| [getShowSeriesName()](#getShowSeriesName--) | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de serie para las etiquetas de datos en un gráfico. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Devuelve o establece un Boolean para indicar el comportamiento de visualización del nombre de serie para las etiquetas de datos en un gráfico. |
| [getShowPercentage()](#getShowPercentage--) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representa el comportamiento de visualización de líneas guía de la etiqueta de datos de un gráfico especificado. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representa el comportamiento de visualización de líneas guía de la etiqueta de datos de un gráfico especificado. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determina si la etiqueta de datos de un gráfico especificado se mostrará como una llamada de datos o como una etiqueta de datos. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determina si la etiqueta de datos de un gráfico especificado se mostrará como una llamada de datos o como una etiqueta de datos. |
| [getSeparator()](#getSeparator--) | Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. |
| [getTextFormat()](#getTextFormat--) | Devuelve el formato de texto del gráfico. |
| [getChart()](#getChart--) | Devuelve el gráfico. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Lectura/escritura booleano.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad IsNumberFormatLinkedToSource para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad IsNumberFormatLinkedToSource para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" hace que todas DataLabels.get_Item(i).isNumberFormatLinkedToSource() sean iguales a val).

**Devuelve:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Lectura/escritura booleano.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad IsNumberFormatLinkedToSource para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad IsNumberFormatLinkedToSource para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" hace que todas DataLabels.get_Item(i).isNumberFormatLinkedToSource() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Representa la cadena de formato para el objeto DataLabels. Lectura/escritura String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection. Cuando se asigna un valor a esta propiedad, ese valor también se asigna a la propiedad NumberFormat para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hace que todas DataLabels.get_Item(i).getNumberFormat() sean iguales a val).

**Devuelve:**
java.lang.String
### setNumberFormat(java.lang.String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Representa la cadena de formato para el objeto DataLabels. Lectura/escritura String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection. Cuando se asigna un valor a esta propiedad, ese valor también se asigna a la propiedad NumberFormat para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hace que todas DataLabels.get_Item(i).getNumberFormat() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representa el formato de la etiqueta de datos. Solo lectura [IFormat](../../com.aspose.slides/iformat).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad representa el formato predeterminado para las nuevas etiquetas de datos en la colección DataLabelCollection.

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Representa la posición de la etiqueta de datos. Lectura/escritura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection. Representa la posición para los objetos DataLabel. Establecer esta propiedad con un valor también establece este valor en la propiedad Position para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" hace que todas DataLabels.get_Item(i).getPosition() sean iguales a val).

**Devuelve:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representa la posición de la etiqueta de datos. Lectura/escritura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection. Representa la posición para los objetos DataLabel. Establecer esta propiedad con un valor también establece este valor en la propiedad Position para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" hace que todas DataLabels.get_Item(i).getPosition() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. True si la clave de leyenda de la etiqueta de datos es visible. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLegendKey para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" hace que todas DataLabels.get_Item(i).getShowLegendKey() sean iguales a val).

**Devuelve:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. True si la clave de leyenda de la etiqueta de datos es visible. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowLegendKey para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" hace que todas DataLabels.get_Item(i).getShowLegendKey() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowValue para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowValue para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" hace que todas DataLabels.get_Item(i).getShowValue() sean iguales a val).

**Devuelve:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowValue para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowValue para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" hace que todas DataLabels.get_Item(i).getShowValue() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True muestra el nombre de categoría para las etiquetas de datos en un gráfico. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también establece este valor en la propiedad ShowCategoryName para todas las etiquetas de datos en la colección DataLabelCollection (p.ej. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" hace que todas DataLabels.get_Item(i).getShowCategoryName() sean iguales a val).

**Devuelve:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True muestra el nombre de categoría para las etiquetas de datos en un gráfico. False lo oculta. Lectura/escritura boolean.

--------------------
Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowCategoryName para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" provoca que todos DataLabels.get_Item(i).getShowCategoryName() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Obtiene o establece un Boolean que indica el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. True para mostrar el nombre de la serie. False para ocultarlo. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowSeriesName para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" provoca que todos DataLabels.get_Item(i).getShowSeriesName() sean iguales a val).

**Devuelve:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Obtiene o establece un Boolean que indica el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. True para mostrar el nombre de la serie. False para ocultarlo. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowSeriesName para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" provoca que todos DataLabels.get_Item(i).getShowSeriesName() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor del porcentaje. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowPercentage para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" provoca que todos DataLabels.get_Item(i).getShowPercentage() sean iguales a val).

**Devuelve:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor del porcentaje. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowPercentage para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" provoca que todos DataLabels.get_Item(i).getShowPercentage() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Representa el comportamiento de visualización del valor de tamaño de burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de burbuja. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowBubbleSize para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" provoca que todos DataLabels.get_Item(i).getShowBubbleSize() sean iguales a val).

**Devuelve:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Representa el comportamiento de visualización del valor de tamaño de burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de burbuja. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowBubbleSize para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" provoca que todos DataLabels.get_Item(i).getShowBubbleSize() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. False las oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLeaderLines para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" provoca que todos DataLabels.get_Item(i).getShowLeaderLines() sean iguales a val).

**Devuelve:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. False las oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLeaderLines para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" provoca que todos DataLabels.get_Item(i).getShowLeaderLines() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLabelValueFromCell para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" provoca que todos DataLabels.get_Item(i).getShowLabelValueFromCell() sean iguales a val).

**Devuelve:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. False lo oculta. Lectura/escritura boolean.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLabelValueFromCell para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" provoca que todos DataLabels.get_Item(i).getShowLabelValueFromCell() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" provoca que todos DataLabels.get_Item(i).getShowLabelAsDataCallout() sean iguales a val).

**Devuelve:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad ShowLabelAsDataCallout para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" provoca que todos DataLabels.get_Item(i).getShowLabelAsDataCallout() sean iguales a val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. Lectura/escritura String.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad Separator para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" provoca que todos DataLabels.get_Item(i).getSeparator() sean iguales a val).

**Devuelve:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. Lectura/escritura String.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también asigna este valor a la propiedad Separator para todas las etiquetas de datos en la colección DataLabelCollection (por ejemplo, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" provoca que todos DataLabels.get_Item(i).getSeparator() sean iguales a val).
**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Devuelve el formato de texto del gráfico. Solo lectura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Devuelve:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Devuelve el gráfico. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)