---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Representa categorías de gráfico.
type: docs
url: /es/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Representa categorías de gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral if UseCell is false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral if UseCell is false. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getCachedValue()](#getCachedValue--) | Gets the cached value of a chart category. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Si es true, la propiedad AsCell está activa. En otras palabras, la hoja de cálculo se utiliza para almacenar la categoría (este caso soporta una categoría de varios niveles). Si es false, la propiedad AsLiteral está activa. En otras palabras, la hoja de cálculo NO se utiliza para almacenar la categoría (y este caso no soporta categorías de varios niveles). Booleano de solo lectura.

--------------------

Para cambiar el valor de esta propiedad (para todas las categorías en la colección) establezca el nuevo valor a la propiedad [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Devuelve:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Devuelve o establece el objeto IChartDataCell. Si la categoría es de varios niveles, se utiliza el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Devuelve o establece el objeto IChartDataCell. Si la categoría es de varios niveles, se utiliza el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Devuelve o establece AsLiteral si UseCell es false. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Devuelve o establece AsLiteral si UseCell es false. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Si UseCell es true, entonces esta propiedad representa la propiedad AsCell.Value. Si UseCell es false, entonces esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Si UseCell es true, entonces esta propiedad representa la propiedad AsCell.Value. Si UseCell es false, entonces esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Obtiene el valor almacenado en caché de una categoría de gráfico. Solo lectura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Imprime todos los valores de categoría del gráfico almacenados en caché.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Contenedor gestionado de los valores de los niveles de agrupación de la categoría de gráfico. Una categoría de varios niveles contiene más de un nivel de agrupación. La indexación de los niveles de agrupación comienza en cero. Solo lectura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Devuelve:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Elimina la categoría del gráfico.