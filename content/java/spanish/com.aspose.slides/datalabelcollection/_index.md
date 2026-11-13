---
title: DataLabelCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa etiquetas de serie.
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

Representa etiquetas de serie.
## Métodos

| Method | Description |
| --- | --- |
| [getChart()](#getChart--) | Devuelve el gráfico padre. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [isVisible()](#isVisible--) | False significa que la etiqueta de datos no es visible por defecto (y así todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son false). |
| [hide()](#hide--) | Oculta la etiqueta de datos por defecto estableciendo todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtiene el número de etiquetas de datos visibles en la colección. |
| [getCount()](#getCount--) | Obtiene el número total de etiquetas de datos en la colección. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Obtiene el formato predeterminado de la etiqueta de datos. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representa el formato de líneas guía de las etiquetas de datos. |
| [getParentSeries()](#getParentSeries--) | Obtiene la serie padre. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Devuelve el índice de la DataLabel especificada en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene la etiqueta de datos para el punto de datos con el índice especificado. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Obtiene o establece el tipo de forma predeterminado para las etiquetas de datos. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Obtiene o establece el tipo de forma predeterminado para las etiquetas de datos. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre de un FillFormat. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación padre de un FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Devuelve el gráfico padre. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un java.util.Iterator para toda la colección.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False significa que la etiqueta de datos no es visible por defecto (y así todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat son false). Solo lectura boolean.

--------------------

Si la etiqueta de datos es visible por defecto, puedes ocultarla por defecto con el método Hide(). Pero si la etiqueta de datos no es visible por defecto (IsVisible es false), puedes hacer que la etiqueta de datos "visible por defecto" configurando las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat a estado true.

**Devuelve:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Oculta la etiqueta de datos por defecto estableciendo todas las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat en estado false. IsVisible será false después de esto.

--------------------

Si la etiqueta de datos no es visible por defecto (IsVisible es false) puedes hacer que la etiqueta de datos "visible por defecto" configurando las banderas Show\*-flags (ShowValue, ...) de la propiedad DefaultDataLabelFormat a estado true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Obtiene el número de etiquetas de datos visibles en la colección. Solo lectura int.

**Devuelve:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Obtiene el número total de etiquetas de datos en la colección. Solo lectura int.

**Devuelve:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Obtiene el formato predeterminado de la etiqueta de datos. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Devuelve:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
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


**Devuelve:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Obtiene la serie padre. Solo lectura [IChartSeries](../../com.aspose.slides/ichartseries).

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Devuelve el índice de la DataLabel especificada en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel a buscar. |

**Devuelve:**
int - Índice de una DataLabel o -1 si la DataLabel no pertenece a esta colección.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Obtiene la etiqueta de datos para el punto de datos con el índice especificado.

--------------------

Manera alternativa de acceder a la etiqueta de datos es: - series.getDataPoints().get_Item(i).getLabel() - gestionar propiedades de la etiqueta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Obtiene o establece el tipo de forma predeterminado para las etiquetas de datos. Devuelve [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si no se define forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Establece el tipo de forma de todas las etiquetas de datos en la primera serie a Elipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Establecer esta propiedad también establece la propiedad IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) para todas las etiquetas de datos en la colección al mismo valor.

**Devuelve:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Obtiene o establece el tipo de forma predeterminado para las etiquetas de datos. Devuelve [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si no se define forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Establece el tipo de forma de todas las etiquetas de datos en la primera serie a Elipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Establecer esta propiedad también establece la propiedad IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) para todas las etiquetas de datos en la colección al mismo valor.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva padre de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación padre de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)