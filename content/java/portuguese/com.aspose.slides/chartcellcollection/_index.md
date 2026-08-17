---
title: ChartCellCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de células com dados.
type: docs
url: /pt/com.aspose.slides/chartcellcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject  
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Representa uma coleção de células com dados.

## Métodos

| Método | Descrição |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Retorna o endereço do conjunto de células na pasta de trabalho. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | String de concatenação de todos os valores de string das células. |
| [get_Item(int index)](#get-Item-int-) | Retorna uma célula (IChartDataCell) por índice. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Adiciona nova célula à coleção. |
| [add(Object value)](#add-java.lang.Object-) | Cria [ChartDataCell](../../com.aspose.slides/chartdatacell) a partir do valor especificado e o adiciona à coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove uma célula da coleção por índice. |
| [getCount()](#getCount--) | Obtém a contagem de células na coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Retorna o endereço do conjunto de células na pasta de trabalho.

**Returns:**  
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

String de concatenação de todos os valores de string das células.

**Returns:**  
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Retorna uma célula (IChartDataCell) por índice.

**Parameters:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma célula. |

**Returns:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Célula com dados.

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Adiciona nova célula à coleção.

**Parameters:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nova célula a ser adicionada. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Cria [ChartDataCell](../../com.aspose.slides/chartdatacell) a partir do valor especificado e o adiciona à coleção.

**Parameters:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object | O valor.

--------------------

Este método adiciona uma planilha com o nome AUTO\_DATA e insere todos os valores lá. Se você usar [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) para adicionar ou editar valores de Cell, certifique-se de não usar esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove uma célula da coleção por índice.

**Parameters:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma célula a ser removida. |

### getCount() {#getCount--}
```
public final int getCount()
```

Obtém a contagem de células na coleção. Somente leitura int.

**Returns:**  
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Retorna um enumerador que itera através da coleção.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Um java.util.Iterator para a coleção inteira.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject