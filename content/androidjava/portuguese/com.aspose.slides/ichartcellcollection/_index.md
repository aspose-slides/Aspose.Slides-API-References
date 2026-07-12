---
title: IChartCellCollection
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa uma coleção de células com dados.
type: docs
url: /pt/com.aspose.slides/ichartcellcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Representa uma coleção de células com dados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Retorna o endereço do conjunto de células na pasta de trabalho. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | String de concatenação de todos os valores de string das células. |
| [get_Item(int index)](#get-Item-int-) | Retorna uma célula (IChartDataCell) por índice. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Adiciona uma nova célula à coleção. |
| [add(Object value)](#add-java.lang.Object-) | Cria [IChartDataCell](../../com.aspose.slides/ichartdatacell) a partir do valor especificado e o adiciona à coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove uma célula da coleção por índice. |
| [getCount()](#getCount--) | Obtém a contagem de células na coleção. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Retorna o endereço do conjunto de células na pasta de trabalho.

**Retorna:**
java.lang.String - Endereço do conjunto de células na pasta de trabalho String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


String de concatenação de todos os valores de string das células.

**Retorna:**
java.lang.String - String resultante String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Retorna uma célula (IChartDataCell) por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma célula. |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Célula com dados.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Adiciona uma nova célula à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nova célula a ser adicionada. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Cria [IChartDataCell](../../com.aspose.slides/ichartdatacell) a partir do valor especificado e o adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | |
| value | java.lang.Object | O valor. |

--------------------

Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores nela. Se você usar [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) para adicionar ou editar valores de Cell, certifique-se de que não use esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove uma célula da coleção por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | |
| index | int | Índice da célula a remover. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtém a contagem de células na coleção. int somente-leitura.

**Retorna:**
int