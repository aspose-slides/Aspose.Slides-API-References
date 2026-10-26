---
title: IChartSeriesCollection
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una colección de
type: docs
url: /es/com.aspose.slides/ichartseriescollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Representa una colección de [IChartSeries](../../com.aspose.slides/ichartseries)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [add(int type)](#add-int-) | Crea una nueva serie de gráfico y la agrega a la colección. |
| [insert(int index, int type)](#insert-int-int-) | Crea una nueva serie de gráfico y la inserta en la colección. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Crea una nueva serie de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) y la agrega a la colección. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Crea una nueva serie de gráfico a partir de [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) y la agrega a la colección. |
| [add(String name, int type)](#add-java.lang.String-int-) | Crea una nueva serie de gráfico a partir de un valor y la agrega a la colección. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Busca el [IChartSeries](../../com.aspose.slides/ichartseries) especificado y devuelve el índice basado en cero de la primera ocurrencia dentro de toda la Colección |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Elimina el valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado |
| [clear()](#clear--) | Elimina todos los elementos (incluido el estilo del gráfico) de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - El elemento en el índice especificado.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
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
public abstract IChartSeries insert(int index, int type)
```

Crea una nueva serie de gráfico y la inserta en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice para la inserción |
| type | int | Tipo de gráfico [ChartType](../../com.aspose.slides/charttype) |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nueva serie de gráfico [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Crea una nueva serie de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Celda que contiene el nombre de la serie. |
| type | int | Tipo establecido de la serie

--------------------

Si la serie del gráfico se crea a partir de la misma celda que ya está en la colección, el método no agrega nada y devuelve su índice. |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie de gráfico agregada o serie que ya está en la colección.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Crea una nueva serie de gráfico a partir de [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Celdas que contienen el nombre de la serie. |
| type | int | Tipo establecido de la serie

--------------------

Si la serie del gráfico se crea a partir de la misma celda que ya está en la colección, el método no agrega nada y devuelve su índice. |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie de gráfico agregada o serie que ya está en la colección.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Crea una nueva serie de gráfico a partir de un valor y la agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la serie. |
| type | int | Tipo establecido de la serie |

**Devuelve:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Serie de gráfico agregada.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Busca el [IChartSeries](../../com.aspose.slides/ichartseries) especificado y devuelve el índice basado en cero de la primera ocurrencia dentro de toda la Colección

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valor de la serie del gráfico. |

**Devuelve:**
int - El índice basado en cero de la primera ocurrencia del valor dentro de toda la CollectionBase, si se encuentra; de lo contrario, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | El valor. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice int |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los elementos (incluido el estilo del gráfico) de la colección.