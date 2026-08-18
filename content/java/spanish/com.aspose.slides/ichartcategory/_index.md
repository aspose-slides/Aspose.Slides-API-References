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
| [getUseCell()](#getUseCell--) | Si es verdadero, la propiedad AsCell es actual. |
| [getAsCell()](#getAsCell--) | Devuelve o establece el objeto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Devuelve o establece el objeto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Devuelve o establece AsLiteral si UseCell es false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Devuelve o establece AsLiteral si UseCell es false. |
| [getValue()](#getValue--) | Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contenedor gestionado de los valores de los niveles de agrupación de categorías del gráfico. |
| [remove()](#remove--) | Elimina la categoría del gráfico. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Si es true la propiedad AsCell es actual. En otras palabras, la hoja de cálculo se utiliza para almacenar la categoría (este caso admite una categoría de varios niveles). Si es false la propiedad AsLiteral es actual. En otras palabras, la hoja de cálculo NO se utiliza para almacenar la categoría (y este caso no admite categorías de varios niveles). Boolean de solo lectura.

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

Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. Si UseCell es false, esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Si UseCell es true, esta propiedad representa la propiedad AsCell.Value. Si UseCell es false, esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Contenedor gestionado de los valores de los niveles de agrupación de categorías del gráfico. La categoría de varios niveles contiene más de un nivel de agrupación. La indexación de los niveles de agrupación comienza en cero. Solo lectura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Devuelve:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Elimina la categoría del gráfico.