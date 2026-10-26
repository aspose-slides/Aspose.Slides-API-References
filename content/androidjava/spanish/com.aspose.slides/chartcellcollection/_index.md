---
title: ChartCellCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una colección de celdas con datos.
type: docs
url: /es/com.aspose.slides/chartcellcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Representa una colección de celdas con datos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Devuelve la dirección del conjunto de celdas en el libro de trabajo. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Cadena de concatenación de los valores de cadena de todas las celdas. |
| [get_Item(int index)](#get-Item-int-) | Devuelve una celda (IChartDataCell) por índice. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Agrega una nueva celda a la colección. |
| [add(Object value)](#add-java.lang.Object-) | Crea [ChartDataCell](../../com.aspose.slides/chartdatacell) a partir del valor especificado y lo agrega a la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina una celda de la colección por índice. |
| [getCount()](#getCount--) | Obtiene la cantidad de celdas en la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Devuelve la dirección del conjunto de celdas en el libro de trabajo.

**Devuelve:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Cadena de concatenación de los valores de cadena de todas las celdas.

**Devuelve:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Devuelve una celda (IChartDataCell) por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una celda. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Celda con datos.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Agrega una nueva celda a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nueva celda a agregar. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Crea [ChartDataCell](../../com.aspose.slides/chartdatacell) a partir del valor especificado y lo agrega a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object | El valor. |

--------------------

Este método agrega una hoja de cálculo con el nombre AUTO_DATA y agrega todos los valores allí. Si usa [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) para agregar o editar valores de Cell, asegúrese de no usar esta hoja de cálculo. El número máximo de valores añadidos usando este método no debe exceder 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina una celda de la colección por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una celda a eliminar. |
### getCount() {#getCount--}
```
public final int getCount()
```


Obtiene la cantidad de celdas en la colección. Solo lectura int.

**Devuelve:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Un java.util.Iterator para toda la colección.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject