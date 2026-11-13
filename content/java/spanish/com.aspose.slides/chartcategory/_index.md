---
title: ChartCategory
second_title: Referencia de API de Aspose.Slides para Java
description: Representa categorías de gráfico.
type: docs
url: /es/com.aspose.slides/chartcategory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Representa categorías de gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getUseCell()](#getUseCell--) | Si es true entonces la propiedad AsCell es actual. |
| [getAsCell()](#getAsCell--) | Devuelve o establece el objeto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Devuelve o establece el objeto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Devuelve o establece el objeto AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Devuelve o establece el objeto AsLiteral. |
| [getValue()](#getValue--) | Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contenedor gestionado de los valores de los niveles de agrupación de categorías del gráfico. |
| [getCachedValue()](#getCachedValue--) | Obtiene el valor en caché de una categoría de gráfico. |
| [remove()](#remove--) | Elimina la categoría del gráfico. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Si es true entonces la propiedad AsCell es actual. En otras palabras, la hoja de cálculo se usa para almacenar la categoría (este caso admite una categoría de varios niveles). Si es false entonces la propiedad AsLiteral es actual. En otras palabras, la hoja de cálculo NO se usa para almacenar la categoría (y este caso no admite categorías de varios niveles). Booleano de solo lectura.

--------------------

Para cambiar el valor de esta propiedad (para todas las categorías en la colección) establezca el nuevo valor en la propiedad ChartCategoryCollection.UseCells.

**Devuelve:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Devuelve o establece el objeto IChartDataCell. Si la categoría es de varios niveles, se utiliza el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Devuelve o establece el objeto IChartDataCell. Si la categoría es de varios niveles, se utiliza el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


Devuelve o establece el objeto AsLiteral. Objeto de lectura/escritura.

**Devuelve:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


Devuelve o establece el objeto AsLiteral. Objeto de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. Si UseCell es false, esta propiedad representa la propiedad AsLiteral. Objeto de lectura/escritura.

**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. Si UseCell es false, esta propiedad representa la propiedad AsLiteral. Objeto de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


Contenedor gestionado de los valores de los niveles de agrupación de categorías del gráfico. La categoría de varios niveles contiene más de un nivel de agrupación. El índice de los niveles de agrupación comienza en cero. Solo lectura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Devuelve:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```


Obtiene el valor en caché de una categoría de gráfico. Solo lectura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Imprima todos los valores en caché de las categorías del gráfico.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**Devuelve:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```


Elimina la categoría del gráfico.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject