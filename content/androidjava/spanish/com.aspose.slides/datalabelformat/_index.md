---
title: DataLabelFormat
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa opciones de formato para DataLabel.
type: docs
url: /es/com.aspose.slides/datalabelformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Representa opciones de formato para DataLabel.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Booleano de lectura/escritura. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Booleano de lectura/escritura. |
| [getNumberFormat()](#getNumberFormat--) | Representa la cadena de formato para el objeto DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa la cadena de formato para el objeto DataLabels. |
| [getFormat()](#getFormat--) | Representa el formato de la etiqueta de datos. |
| [getPosition()](#getPosition--) | Representa la posición de la etiqueta de datos. |
| [setPosition(int value)](#setPosition-int-) | Representa la posición de la etiqueta de datos. |
| [getShowLegendKey()](#getShowLegendKey--) | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. |
| [getShowValue()](#getShowValue--) | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. |
| [getShowCategoryName()](#getShowCategoryName--) | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. |
| [getShowSeriesName()](#getShowSeriesName--) | Devuelve o establece un Booleano que indica el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Devuelve o establece un Booleano que indica el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. |
| [getShowPercentage()](#getShowPercentage--) | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos. |
| [getSeparator()](#getSeparator--) | Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. |
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

Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad IsNumberFormatLinkedToSource para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad IsNumberFormatLinkedToSource de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).isNumberFormatLinkedToSource() devuelvan val).

**Devuelve:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad IsNumberFormatLinkedToSource para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad IsNumberFormatLinkedToSource de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).isNumberFormatLinkedToSource() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Representa la cadena de formato para el objeto DataLabels. String de lectura/escritura.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection. Cuando se asigna un valor a esta propiedad, ese valor también se asigna a la propiedad NumberFormat de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hace que todas las llamadas a DataLabels.get\_Item(i).getNumberFormat() devuelvan val).

**Devuelve:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Representa la cadena de formato para el objeto DataLabels. String de lectura/escritura.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección DataLabelCollection. Cuando se asigna un valor a esta propiedad, ese valor también se asigna a la propiedad NumberFormat de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hace que todas las llamadas a DataLabels.get\_Item(i).getNumberFormat() devuelvan val).

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

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad representa el formato predeterminado para las nuevas etiquetas de datos en la colección DataLabelCollection.

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Representa la posición de la etiqueta de datos. Lectura/escritura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection. Representa la posición de los objetos DataLabel. Establecer esta propiedad con un valor también lo asigna a la propiedad Position de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setPosition(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getPosition() devuelvan val).

**Devuelve:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representa la posición de la etiqueta de datos. Lectura/escritura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad Position para las nuevas etiquetas de datos en la colección DataLabelCollection. Representa la posición de los objetos DataLabel. Establecer esta propiedad con un valor también lo asigna a la propiedad Position de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setPosition(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getPosition() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLegendKey de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLegendKey() devuelvan val).

**Devuelve:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. Verdadero si la clave de leyenda de la etiqueta de datos es visible. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLegendKey para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLegendKey de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLegendKey() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowValue para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowValue de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowValue() devuelvan val).

**Devuelve:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowValue para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowValue de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowValue() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. Verdadero muestra el nombre de categoría para las etiquetas de datos en un gráfico. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowCategoryName de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowCategoryName() devuelvan val).

**Devuelve:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. Verdadero muestra el nombre de categoría para las etiquetas de datos en un gráfico. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowCategoryName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowCategoryName de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowCategoryName() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Devuelve o establece un Booleano que indica el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. Verdadero muestra el nombre de la serie. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowSeriesName de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowSeriesName() devuelvan val).

**Devuelve:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Devuelve o establece un Booleano que indica el comportamiento de visualización del nombre de la serie para las etiquetas de datos en un gráfico. Verdadero muestra el nombre de la serie. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowSeriesName para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowSeriesName de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowSeriesName() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowPercentage de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowPercentage() devuelvan val).

**Devuelve:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Representa el comportamiento de visualización del valor porcentual de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor porcentual. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowPercentage para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowPercentage de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowPercentage() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor del tamaño de burbuja. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowBubbleSize de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowBubbleSize() devuelvan val).

**Devuelve:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor del tamaño de burbuja. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowBubbleSize para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowBubbleSize de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowBubbleSize() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. Verdadero muestra las líneas guía. Falso las oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLeaderLines de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLeaderLines() devuelvan val).

**Devuelve:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. Verdadero muestra las líneas guía. Falso las oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLeaderLines para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLeaderLines de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLeaderLines() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de celda. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLabelValueFromCell de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLabelValueFromCell() devuelvan val).

**Devuelve:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Representa el comportamiento de visualización del valor de celda de la etiqueta de datos de un gráfico especificado. Verdadero muestra el valor de celda. Falso lo oculta. Booleano de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelValueFromCell para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLabelValueFromCell de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLabelValueFromCell() devuelvan val).

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

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLabelAsDataCallout de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLabelAsDataCallout() devuelvan val).

**Devuelve:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Determina si la etiqueta de datos de un gráfico especificado se mostrará como llamada de datos o como etiqueta de datos.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad ShowLabelAsDataCallout para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad ShowLabelAsDataCallout de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getShowLabelAsDataCallout() devuelvan val).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. String de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad Separator de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getSeparator() devuelvan val).

**Devuelve:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Establece o devuelve un Variant que representa el separador utilizado para las etiquetas de datos en un gráfico. String de lectura/escritura.

--------------------

Si el padre de este objeto DataLabelFormat es una colección DataLabelCollection de etiquetas de datos, esta propiedad obtiene o establece el valor predeterminado de la propiedad Separator para las nuevas etiquetas de datos en la colección DataLabelCollection. Establecer esta propiedad con un valor también lo asigna a la propiedad Separator de todas las etiquetas de datos en la colección DataLabelCollection (p. ej., "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" provoca que todas las llamadas a DataLabels.get\_Item(i).getSeparator() devuelvan val).

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