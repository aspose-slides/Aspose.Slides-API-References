---
title: ChartSeriesCollection
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una colección de
type: docs
url: /es/com.aspose.slides/chartseriescollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Representa la colección de [ChartSeries](../../com.aspose.slides/chartseries)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [size()](#size--) | Devuelve el número de objetos en la colección. |
| [add(int type)](#add-int-) | Crea una nueva serie de gráfico y la agrega a la colección. |
| [insert(int index, int type)](#insert-int-int-) | Crea una nueva serie de gráfico y la inserta en la colección. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Crea una nueva serie de gráfico a partir de [ChartDataCell](../../com.aspose.slides/chartdatacell) y la agrega a la colección. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Crea una nueva serie de gráfico a partir de [ChartCellCollection](../../com.aspose.slides/chartcellcollection) y la agrega a la colección. |
| [add(String name, int type)](#add-java.lang.String-int-) | Crea una nueva serie de gráfico a partir de un valor y la agrega a la colección. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Busca el [ChartSeries](../../com.aspose.slides/chartseries) especificado y devuelve el índice basado en cero de la primera aparición dentro de toda la colección. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Elimina el valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina un control ActiveX almacenado en la posición especificada de la colección. |
| [clear()](#clear--) | Elimina todos los controles de la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia toda la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - El elemento en el índice especificado.
### size() {#size--}
```
public final int size()
```

Devuelve el número de objetos en la colección. Int de solo lectura.

**Devuelve:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Crea una nueva serie de gráfico y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | Tipo de serie |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nueva serie de gráfico.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Crea una nueva serie de gráfico y la inserta en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Crea una nueva serie de gráfico a partir de [ChartDataCell](../../com.aspose.slides/chartdatacell) y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Celda que contiene el nombre de la serie. |
| type | int | Tipo establece tipo de la serie |

--------------------
Si la serie de gráfico creada a partir de la misma celda ya está en la colección, el método no agrega nada y devuelve su índice. |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie de gráfico agregada o serie que ya está en la colección.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Crea una nueva serie de gráfico a partir de [ChartCellCollection](../../com.aspose.slides/chartcellcollection) y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Celdas que contienen el nombre de la serie. |
| type | int | Tipo establece tipo de la serie |

--------------------
Si la serie de gráfico creada a partir de la misma celda ya está en la colección, el método no agrega nada y devuelve su índice. |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie de gráfico agregada o serie que ya está en la colección.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Crea una nueva serie de gráfico a partir de un valor y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la serie. |
| type | int | Tipo establece tipo de la serie |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie de gráfico agregada.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Busca el [ChartSeries](../../com.aspose.slides/chartseries) especificado y devuelve el índice basado en cero de la primera aparición dentro de toda la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valor de la serie de gráfico. |

**Devuelve:**
int - El índice basado en cero de la primera aparición del valor dentro de toda la CollectionBase, si se encuentra; de lo contrario, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | El valor. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina un control ActiveX almacenado en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del control a eliminar. |
### clear() {#clear--}
```
public final void clear()
```

Elimina todos los controles de la colección.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Un java.util.Iterator para toda la colección.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia toda la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino |
| index | int | Índice en el array de destino. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Boolean de solo lectura.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Objeto de solo lectura.

**Devuelve:**
java.lang.Object