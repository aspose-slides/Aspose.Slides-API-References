---
title: ChartCategory
second_title: Aspose.Slides para Android mediante referencia de API Java
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
| [getUseCell()](#getUseCell--) | Si es verdadero, la propiedad AsCell es actual. |
| [getAsCell()](#getAsCell--) | Devuelve o establece el objeto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Devuelve o establece el objeto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Devuelve o establece el objeto AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Devuelve o establece el objeto AsLiteral. |
| [getValue()](#getValue--) | Si UseCell es verdadero, esta propiedad representa la propiedad AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell es verdadero, esta propiedad representa la propiedad AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contenedor gestionado de los valores de los niveles de agrupación de categorías del gráfico. |
| [remove()](#remove--) | Elimina la categoría del gráfico. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Si es verdadero, la propiedad AsCell es actual. En otras palabras, la hoja de cálculo se usa para almacenar la categoría (este caso admite una categoría multinivel). Si es falso, la propiedad AsLiteral es actual. En otras palabras, la hoja de cálculo NO se usa para almacenar la categoría (y este caso no admite categorías multinivel). Solo lectura booleano.

--------------------

Para cambiar el valor de esta propiedad (para todas las categorías en la colección) establezca el nuevo valor en la propiedad ChartCategoryCollection.UseCells.

**Devuelve:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Devuelve o establece el objeto IChartDataCell. Si la categoría es multinivel, se usa el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Devuelve o establece el objeto IChartDataCell. Si la categoría es multinivel, se usa el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Devuelve o establece el objeto AsLiteral. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Devuelve o establece el objeto AsLiteral. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

Si UseCell es verdadero, esta propiedad representa la propiedad AsCell.Value. Si UseCell es falso, esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Si UseCell es verdadero, esta propiedad representa la propiedad AsCell.Value. Si UseCell es falso, esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Contenedor gestionado de los valores de los niveles de agrupación de categorías del gráfico. Una categoría multinivel contiene más de un nivel de agrupación. La indexación de los niveles de agrupación comienza en cero. Solo lectura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Devuelve:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
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