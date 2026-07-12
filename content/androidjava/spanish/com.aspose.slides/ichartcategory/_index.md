---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart categories.
type: docs
url: /es/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Representa categorías de gráficos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getUseCell()](#getUseCell--) | Si es verdadero entonces la propiedad AsCell es actual. |
| [getAsCell()](#getAsCell--) | Obtiene o asigna el objeto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Obtiene o asigna el objeto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Obtiene o asigna AsLiteral si UseCell es falso. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Obtiene o asigna AsLiteral si UseCell es falso. |
| [getValue()](#getValue--) | Si UseCell es verdadero entonces esta propiedad representa la propiedad AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Si UseCell es verdadero entonces esta propiedad representa la propiedad AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contenedor administrado de los valores de los niveles de agrupación de la categoría del gráfico. |
| [remove()](#remove--) | Elimina la categoría del gráfico. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Si es verdadero entonces la propiedad AsCell es actual. En otras palabras, la hoja de cálculo se utiliza para almacenar la categoría (este caso admite una categoría multinivel). Si es falso entonces la propiedad AsLiteral es actual. En otras palabras, la hoja de cálculo NO se utiliza para almacenar la categoría (y este caso no admite categorías multinivel). Boolean de solo lectura.

--------------------

Para cambiar el valor de esta propiedad (para todas las categorías en la colección) establezca el nuevo valor en la propiedad [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Devuelve:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Obtiene o asigna el objeto IChartDataCell. Si la categoría es multinivel entonces se usa el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Obtiene o asigna el objeto IChartDataCell. Si la categoría es multinivel entonces se usa el objeto IChartDataCell para el nivel "0". Lectura/escritura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Obtiene o asigna AsLiteral si UseCell es falso. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Obtiene o asigna AsLiteral si UseCell es falso. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Si UseCell es verdadero entonces esta propiedad representa la propiedad AsCell.Value. Si UseCell es falso entonces esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Si UseCell es verdadero entonces esta propiedad representa la propiedad AsCell.Value. Si UseCell es falso entonces esta propiedad representa la propiedad AsLiteral. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Contenedor administrado de los valores de los niveles de agrupación de la categoría del gráfico. La categoría multinivel contiene más de un nivel de agrupación. La indexación de los niveles de agrupación comienza en cero. Solo lectura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Devuelve:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Elimina la categoría del gráfico.