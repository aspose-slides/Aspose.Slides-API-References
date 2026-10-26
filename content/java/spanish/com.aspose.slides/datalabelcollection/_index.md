---
title: DataLabelCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa las etiquetas de una serie.
type: docs
url: /es/com.aspose.slides/datalabelcollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Representa las etiquetas de la serie.
## Métodos

| Método | Descripción |
| --- | --- |
| [getChart()](#getChart--) | Devuelve el gráfico principal. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [isVisible()](#isVisible--) | False significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas). |
| [hide()](#hide--) | Oculta la etiqueta de datos por defecto estableciendo todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado falso. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtiene el número de etiquetas de datos visibles en la colección. |
| [getCount()](#getCount--) | Obtiene el número de todas las etiquetas de datos en la colección. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Obtiene el formato predeterminado de la etiqueta de datos. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representa el formato de líneas guía de las etiquetas de datos. |
| [getParentSeries()](#getParentSeries--) | Obtiene la serie principal. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Devuelve un índice del DataLabel especificado en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene la etiqueta de datos para el punto de datos con el índice especificado. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el gráfico principal. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:** com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:** com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un java.util.Iterator para toda la colección.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas). Solo lectura boolean.

--------------------

Si la etiqueta de datos es visible por defecto, puede ocultarla por defecto con el método Hide(). Pero si la etiqueta de datos no es visible por defecto (IsVisible es false) puede hacer que la etiqueta de datos sea "visible por defecto" configurando las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado verdadero.

**Devuelve:** boolean

### hide() {#hide--}
```
public final void hide()
```

Oculta la etiqueta de datos por defecto estableciendo todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado falso. IsVisible será false después de esto.

--------------------

Si la etiqueta de datos no es visible por defecto (IsVisible es false) puede hacer que la etiqueta de datos sea "visible por defecto" configurando las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado verdadero.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Obtiene el número de etiquetas de datos visibles en la colección. Solo lectura int.

**Devuelve:** int

### getCount() {#getCount--}
```
public final int getCount()
```

Obtiene el número de todas las etiquetas de datos en la colección. Solo lectura int.

**Devuelve:** int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Obtiene el formato predeterminado de la etiqueta de datos. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Devuelve:** [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Representa el formato de líneas guía de las etiquetas de datos. Solo lectura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:** [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Obtiene la serie principal. Solo lectura [IChartSeries](../../com.aspose.slides/ichartseries).

**Devuelve:** [IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Devuelve un índice del DataLabel especificado en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel a buscar. |

**Devuelve:** int - Índice de un DataLabel o -1 si el DataLabel no pertenece a esta colección.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Obtiene la etiqueta de datos para el punto de datos con el índice especificado.

--------------------

Una forma alternativa de acceder a la etiqueta de datos es: - series.getDataPoints().get\_Item(i).getLabel() - gestionar las propiedades de la etiqueta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:** [IDataLabel](../../com.aspose.slides/idatalabel)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva principal de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:** [IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación principal de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:** [IPresentation](../../com.aspose.slides/ipresentation)