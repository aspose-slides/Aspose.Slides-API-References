---
title: IChartCategoryCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de
type: docs
url: /es/com.aspose.slides/ichartcategorycollection/
---
**Todas las Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Representa la colección de [IChartCategory](../../com.aspose.slides/ichartcategory)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getUseCells()](#getUseCells--) | Si es verdadero, la hoja de cálculo se usa para almacenar categorías (este caso admite categorías de varios niveles). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Si es verdadero, la hoja de cálculo se usa para almacenar categorías (este caso admite categorías de varios niveles). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Devuelve el número de niveles de agrupación de categorías usados. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Si la categoría existe en la colección, la devuelve. |
| [add(Object value)](#add-java.lang.Object-) | Crea un nuevo [IChartCategory](../../com.aspose.slides/ichartcategory) a partir del valor y lo agrega a la colección. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Busca el [IChartCategory](../../com.aspose.slides/ichartcategory) especificado y devuelve el índice basado en cero de la primera aparición dentro de toda la Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Elimina el valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice proporcionado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - El elemento en el índice especificado.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Si es verdadero, la hoja de cálculo se usa para almacenar categorías (este caso admite categorías de varios niveles). Si es falso, la hoja de cálculo NO se usa para almacenar valores (y este caso no admite categorías de varios niveles). Boolean de lectura/escritura.

**Devuelve:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Si es verdadero, la hoja de cálculo se usa para almacenar categorías (este caso admite categorías de varios niveles). Si es falso, la hoja de cálculo NO se usa para almacenar valores (y este caso no admite categorías de varios niveles). Boolean de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Devuelve el número de niveles de agrupación de categorías usados. Es más de uno para categorías multinivel. int de solo lectura.

**Devuelve:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Si la categoría existe en la colección, la devuelve. De lo contrario crea una nueva categoría de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Celda usada para crear la categoría de gráfico. |

**Devuelve:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Categoría agregada o existente.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Crea un nuevo [IChartCategory](../../com.aspose.slides/ichartcategory) a partir del valor y lo agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object | El valor.

--------------------

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega allí todos los valores. Si utiliza [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) para agregar o editar valores de celdas, asegúrese de no usar esta hoja de cálculo. El número máximo de valores agregados mediante este método no debe exceder 16711680 |

**Devuelve:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Agregado [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Busca el [IChartCategory](../../com.aspose.slides/ichartcategory) especificado y devuelve el índice basado en cero de la primera aparición dentro de toda la Collection.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Categoría de gráfico. |

**Devuelve:**
int - El índice basado en cero de la primera aparición del valor dentro de toda la CollectionBase, si se encuentra; de lo contrario, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | El valor. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice proporcionado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la categoría a eliminar. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los elementos de la colección.