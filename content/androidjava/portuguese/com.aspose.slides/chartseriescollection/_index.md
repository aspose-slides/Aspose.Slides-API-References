---
title: ChartSeriesCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa a coleção de
type: docs
url: /pt/com.aspose.slides/chartseriescollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Representa a coleção de [ChartSeries](../../com.aspose.slides/chartseries)
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [size()](#size--) | Retorna o número de objetos na coleção. |
| [add(int type)](#add-int-) | Cria uma nova série de gráfico e a adiciona à coleção. |
| [insert(int index, int type)](#insert-int-int-) | Cria uma nova série de gráfico e a insere na coleção. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Cria uma nova série de gráfico a partir de [ChartDataCell](../../com.aspose.slides/chartdatacell) e a adiciona à coleção. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Cria uma nova série de gráfico a partir de [ChartCellCollection](../../com.aspose.slides/chartcellcollection) e a adiciona à coleção. |
| [add(String name, int type)](#add-java.lang.String-int-) | Cria uma nova série de gráfico a partir de um valor e a adiciona à coleção. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Procura o [ChartSeries](../../com.aspose.slides/chartseries) especificado e retorna o índice baseado em zero da primeira ocorrência em toda a Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Remove o valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove um controle ActiveX armazenado na posição especificada da coleção. |
| [clear()](#clear--) | Remove todos os controles da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia toda a coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Boolean somente leitura. |
| [getSyncRoot()](#getSyncRoot--) | Retorna a raiz de sincronização. Object somente leitura. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - O elemento no índice especificado.
### size() {#size--}
```
public final int size()
```

Retorna o número de objetos na coleção. int somente leitura.

**Retorna:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Cria uma nova série de gráfico e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | Tipo da série |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nova série de gráfico.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Cria uma nova série de gráfico e a insere na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Cria uma nova série de gráfico a partir de [ChartDataCell](../../com.aspose.slides/chartdatacell) e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Célula que contém o nome da série. |
| type | int | Tipo que define o tipo da série

--------------------

Se a série de gráfico criada a partir da mesma célula já estiver na coleção, então o método não adiciona nada e retorna seu índice. |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de gráfico adicionada ou série que já está na coleção.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Cria uma nova série de gráfico a partir de [ChartCellCollection](../../com.aspose.slides/chartcellcollection) e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Células que contêm o nome da série. |
| type | int | Tipo que define o tipo da série

--------------------

Se a série de gráfico criada a partir da mesma célula já estiver na coleção, então o método não adiciona nada e retorna seu índice. |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de gráfico adicionada ou série que já está na coleção.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Cria uma nova série de gráfico a partir de um valor e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da série. |
| type | int | Tipo que define o tipo da série |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de gráfico adicionada.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Procura o [ChartSeries](../../com.aspose.slides/chartseries) especificado e retorna o índice baseado em zero da primeira ocorrência em toda a Collection

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valor da série de gráfico. |

**Retorna:**
int - O índice baseado em zero da primeira ocorrência de value em toda a CollectionBase, se encontrado; caso contrário, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Remove o valor especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | O valor. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove um controle ActiveX armazenado na posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do controle a ser removido. |

### clear() {#clear--}
```
public final void clear()
```

Remove todos os controles da coleção.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Um java.util.Iterator para toda a coleção.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia toda a coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino |
| index | int | Índice no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Boolean somente leitura.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna a raiz de sincronização. Object somente leitura.

**Retorna:**
java.lang.Object