---
title: ChartCategoryCollection
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una colección de
type: docs
url: /es/com.aspose.slides/chartcategorycollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Representa una colección de [ChartCategory](../../com.aspose.slides/chartcategory)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getUseCells()](#getUseCells--) | Si es true entonces la hoja de cálculo se usa para almacenar categorías (este caso admite categorías multinivel). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Si es true entonces la hoja de cálculo se usa para almacenar categorías (este caso admite categorías multinivel). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Devuelve el recuento de niveles de agrupación de categorías utilizados. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Si la categoría existe en la colección, la devuelve. |
| [add(Object value)](#add-java.lang.Object-) | Crea un nuevo [ChartCategory](../../com.aspose.slides/chartcategory) a partir del valor y lo añade a la colección. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Busca el [ChartCategory](../../com.aspose.slides/chartcategory) especificado y devuelve el índice base cero de la primera aparición dentro de toda la Colección. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Elimina el valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice dado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [size()](#size--) | Devuelve un número de elementos en la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al arreglo especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la Lista está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve un objeto que puede usarse para sincronizar el acceso a la colección. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
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
public final boolean getUseCells()
```

Si es true entonces la hoja de cálculo se usa para almacenar categorías (este caso admite categorías multinivel). Si es false entonces la hoja de cálculo NO se usa para almacenar valores (y este caso no admite categorías multinivel). Lectura/escritura boolean.

**Devuelve:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Si es true entonces la hoja de cálculo se usa para almacenar categorías (este caso admite categorías multinivel). Si es false entonces la hoja de cálculo NO se usa para almacenar valores (y este caso no admite categorías multinivel). Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Devuelve el recuento de niveles de agrupación de categorías usados. Es mayor que uno para categorías multinivel. Solo lectura int.

**Devuelve:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Si la categoría existe en la colección, la devuelve. De lo contrario crea una nueva categoría de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) y la añade a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Celda usada para crear la categoría del gráfico. |

**Devuelve:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Categoria añadida o existente.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Crea un nuevo [ChartCategory](../../com.aspose.slides/chartcategory) a partir del valor y lo añade a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object | El valor. |

--------------------

Este método añade una hoja de cálculo con el nombre AUTO_DATA y agrega todos los valores allí. Si usa [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) para añadir o editar valores de celdas, asegúrese de no usar esta hoja de cálculo. El número máximo de valores agregados usando este método no debe superar 16711680 |

**Devuelve:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Añadido [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Busca el [ChartCategory](../../com.aspose.slides/chartcategory) especificado y devuelve el índice base cero de la primera aparición dentro de toda la Colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Categoría del gráfico. |

**Devuelve:**
int - El índice base cero de la primera aparición del valor dentro de toda la CollectionBase, si se encuentra; de lo contrario, -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | El valor. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice dado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una categoría a eliminar. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los elementos de la colección.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un IGenericEnumerator que puede usarse para recorrer la colección.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Un java.util.Iterator para toda la colección.

### size() {#size--}
```
public final int size()
```

Devuelve un número de elementos en la colección. Solo lectura int.

**Devuelve:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al arreglo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Arreglo de destino. |
| index | int | Índice inicial en el arreglo. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la Lista está sincronizado (seguro para subprocesos). Solo lectura boolean.

**Devuelve:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve un objeto que puede usarse para sincronizar el acceso a la colección. Solo lectura Object.

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object