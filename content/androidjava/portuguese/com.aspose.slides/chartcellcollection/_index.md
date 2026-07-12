---
title: ChartCellCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de células com dados.
type: docs
url: /pt/com.aspose.slides/chartcellcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Representa uma coleção de células com dados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Returns address of the set of cells in workbook. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Concatenation string from all cells string values. |
| [get_Item(int index)](#get-Item-int-) | Returns a cell (IChartDataCell) by index. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Add new cell to the collection. |
| [add(Object value)](#add-java.lang.Object-) | Creates [ChartDataCell](../../com.aspose.slides/chartdatacell) from specified value and adds it to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a cell from the collection by index. |
| [getCount()](#getCount--) | Gets the count of cells in collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Retorna o endereço do conjunto de células na pasta de trabalho.

**Retorna:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Concatena as strings de todos os valores das células.

**Retorna:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Retorna uma célula (IChartDataCell) por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma célula. |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell com dados.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Adiciona nova célula à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nova célula a ser adicionada. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Cria [ChartDataCell](../../com.aspose.slides/chartdatacell) a partir do valor especificado e o adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object | O valor.

--------------------

Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores lá. Se você usar [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) para adicionar ou editar valores de Cell, certifique-se de que não utiliza esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove uma célula da coleção por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma célula a ser removida. |

### getCount() {#getCount--}
```
public final int getCount()
```

Obtém a contagem de células na coleção. Somente leitura int.

**Retorna:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Um java.util.Iterator para a coleção inteira.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject