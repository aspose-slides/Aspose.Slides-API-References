---
title: ChartCategoryCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa coleção de
type: docs
url: /pt/com.aspose.slides/chartcategorycollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Representa coleção de [ChartCategory](../../com.aspose.slides/chartcategory)
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getUseCells()](#getUseCells--) | Se verdadeiro, a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Se verdadeiro, a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Retorna a contagem dos níveis de agrupamento de categorias usados. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Se a categoria existir na coleção, retorná-la. |
| [add(Object value)](#add-java.lang.Object-) | Cria um novo [ChartCategory](../../com.aspose.slides/chartcategory) a partir do valor e o adiciona à coleção. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Procura o [ChartCategory](../../com.aspose.slides/chartcategory) especificado e retorna o índice baseado em zero da primeira ocorrência dentro de toda a Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Remove o valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice fornecido. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para toda a coleção. |
| [size()](#size--) | Retorna o número de elementos na coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à List está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna um objeto que pode ser usado para sincronizar o acesso à coleção. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - O elemento no índice especificado.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Se verdadeiro, a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). Se falso, a planilha NÃO é usada para armazenar valores (e este caso não suporta categorias de múltiplos níveis). Boolean de leitura/escrita.

**Retorno:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Se verdadeiro, a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). Se falso, a planilha NÃO é usada para armazenar valores (e este caso não suporta categorias de múltiplos níveis). Boolean de leitura/escrita.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Retorna a contagem dos níveis de agrupamento de categorias usados. É maior que um para categorias de múltiplos níveis. Int de somente leitura.

**Retorno:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Se a categoria existir na coleção, retorná-la. Caso contrário, cria uma nova categoria de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Célula usada para criar a categoria de gráfico. |

**Retorno:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Categoria adicionada ou existente.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Cria um novo [ChartCategory](../../com.aspose.slides/chartcategory) a partir do valor e o adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object | O valor.

--------------------

Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores nela. Se você usar [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) para adicionar ou editar valores de célula, certifique-se de não usar esta planilha. O número máximo de valores adicionados por este método não deve exceder 16711680 |

**Retorno:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) adicionado.
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Procura o [ChartCategory](../../com.aspose.slides/chartcategory) especificado e retorna o índice baseado em zero da primeira ocorrência dentro de toda a Collection.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Categoria de gráfico. |

**Retorno:**
int - O índice baseado em zero da primeira ocorrência de value dentro de toda a CollectionBase, se encontrado; caso contrário, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Remove o valor especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | O valor. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o elemento no índice fornecido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da categoria a ser removida. |
### clear() {#clear--}
```
public final void clear()
```

Remove todos os elementos da coleção.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Retorna um iterator java para toda a coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Um java.util.Iterator para toda a coleção.
### size() {#size--}
```
public final int size()
```

Retorna o número de elementos na coleção. Int somente leitura.

**Retorno:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à List está sincronizado (thread-safe). Boolean somente leitura.

**Retorno:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna um objeto que pode ser usado para sincronizar o acesso à coleção. Object somente leitura.

Retorna uma raiz de sincronização. Object somente leitura.

**Retorno:**
java.lang.Object