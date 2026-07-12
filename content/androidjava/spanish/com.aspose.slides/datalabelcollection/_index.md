---
title: DataLabelCollection
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa etiquetas de serie.
type: docs
url: /es/com.aspose.slides/datalabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Representa etiquetas de serie.
## Métodos

| Método | Descripción |
| --- | --- |
| [getChart()](#getChart--) | Returns the parent chart. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [isVisible()](#isVisible--) | False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). |
| [hide()](#hide--) | Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Gets the number of visible data labels in the collection. |
| [getCount()](#getCount--) | Gets the number of all data labels in the collection. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Gets the default data label format. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Represents data labels leader lines format. |
| [getParentSeries()](#getParentSeries--) | Gets the parent series. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returns an index of the specified DataLabel in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the data label for the data point with the specified index. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
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

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel} - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel} - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Solo lectura boolean.

--------------------

Si la etiqueta de datos es visible por defecto, puede ocultarla por defecto con el método Hide(). Pero si la etiqueta de datos no es visible por defecto (IsVisible es false) puede hacerla "visible por defecto" estableciendo los flags Show\*- (ShowValue, ...) de la propiedad DefaultDataLabelFormat a true.

**Devuelve:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this.

--------------------

Si la etiqueta de datos no es visible por defecto (IsVisible es false) puede hacerla "visible por defecto" estableciendo los flags Show\*- (ShowValue, ...) de la propiedad DefaultDataLabelFormat a true state.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Gets the number of visible data labels in the collection. Solo lectura int.

**Devuelve:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of all data labels in the collection. Solo lectura int.

**Devuelve:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Gets the default data label format. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Devuelve:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Represents data labels leader lines format. Solo lectura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
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


Gets the parent series. Solo lectura [IChartSeries](../../com.aspose.slides/ichartseries).

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Returns an index of the specified DataLabel in the collection.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Devuelve:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Gets the data label for the data point with the specified index.

--------------------

Una forma alternativa de acceder a la etiqueta de datos es: - series.getDataPoints().get_Item(i).getLabel() - manage label properties.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)