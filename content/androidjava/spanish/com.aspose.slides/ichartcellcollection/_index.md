---
title: IChartCellCollection
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa una colección de celdas con datos.
type: docs
url: /es/com.aspose.slides/ichartcellcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Representa una colección de celdas con datos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Devuelve la dirección del conjunto de celdas en el libro de trabajo. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Cadena de concatenación de los valores de cadena de todas las celdas. |
| [get_Item(int index)](#get-Item-int-) | Devuelve una celda (IChartDataCell) por índice. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Añade una nueva celda a la colección. |
| [add(Object value)](#add-java.lang.Object-) | Crea [IChartDataCell](../../com.aspose.slides/ichartdatacell) a partir del valor especificado y lo añade a la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina una celda de la colección por índice. |
| [getCount()](#getCount--) | Obtiene el recuento de celdas en la colección. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Devuelve la dirección del conjunto de celdas en el libro de trabajo.

**Devuelve:**
java.lang.String - Dirección del conjunto de celdas en el libro de trabajo String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Cadena de concatenación de los valores de cadena de todas las celdas.

**Devuelve:**
java.lang.String - Cadena resultante String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Devuelve una celda (IChartDataCell) por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una celda. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Celda con datos.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Añade una nueva celda a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nueva celda a añadir. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Crea [IChartDataCell](../../com.aspose.slides/ichartdatacell) a partir del valor especificado y lo añade a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object | El valor. |

--------------------

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y añade todos los valores allí. Si utilizas [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) para añadir o editar valores de celda, asegúrate de no usar esta hoja de cálculo. El número máximo de valores añadidos mediante este método no debe superar 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina una celda de la colección por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la celda a eliminar. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtiene el recuento de celdas en la colección. Solo lectura int.

**Devuelve:**
int