---
title: IDataLabelCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa las etiquetas de una serie.
type: docs
url: /es/com.aspose.slides/idatalabelcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Representa las etiquetas de una serie.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene la etiqueta de datos para el punto de datos con el índice especificado. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Devuelve el formato predeterminado de todas las etiquetas de datos en la colección. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representa el formato de líneas guía de las etiquetas de datos. |
| [isVisible()](#isVisible--) | False significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas). |
| [hide()](#hide--) | Oculta la etiqueta de datos por defecto estableciendo todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado falso. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtiene el número de etiquetas de datos visibles en la colección. |
| [getCount()](#getCount--) | Obtiene el número total de etiquetas de datos en la colección. |
| [getParentSeries()](#getParentSeries--) | Devuelve la serie de gráfico principal. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Devuelve un índice del DataLabel especificado en la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Obtiene la etiqueta de datos para el punto de datos con el índice especificado.

--------------------

Una forma alternativa de acceder a la etiqueta de datos es: - getSeries().getDataPoints().get\_Item(i).getLabel() - gestionar las propiedades de la etiqueta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Devuelve el formato predeterminado de todas las etiquetas de datos en la colección. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Devuelve:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
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


**Devuelve:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False significa que la etiqueta de datos no es visible por defecto (y por lo tanto todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son falsas). Solo lectura boolean.

--------------------

Si la etiqueta de datos es visible por defecto, puede ocultarla por defecto con el método Hide(). Pero si la etiqueta de datos no es visible por defecto (IsVisible es false) puede hacer que la etiqueta de datos sea "visible por defecto" configurando las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado verdadero.

**Devuelve:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Oculta la etiqueta de datos por defecto estableciendo todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado falso. IsVisible será false después de esto.

--------------------

Si la etiqueta de datos no es visible por defecto (IsVisible es false) puede hacer que la etiqueta de datos sea "visible por defecto" configurando las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado verdadero.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Obtiene el número de etiquetas de datos visibles en la colección. Solo lectura int.

**Devuelve:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtiene el número total de etiquetas de datos en la colección. Solo lectura int.

**Devuelve:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Devuelve la serie de gráfico principal. Solo lectura [IChartSeries](../../com.aspose.slides/ichartseries).

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Devuelve un índice del DataLabel especificado en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel a encontrar. |

**Devuelve:**
int - Índice de un DataLabel o -1 si el DataLabel no pertenece a esta colección.