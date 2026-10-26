---
title: ColumnCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de colunas em uma tabela.
type: docs
url: /pt/com.aspose.slides/columncollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Representa a coleção de colunas em uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna o número de colunas em uma coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna a coluna no índice especificado. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Cria uma cópia da linha modelo especificada e a insere no final de uma tabela. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Cria uma cópia da coluna modelo especificada e a insere na posição especificada em uma tabela. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Remove uma coluna na posição especificada de uma tabela. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna a raiz de sincronização. |
### size() {#size--}
```
public final int size()
```


Retorna o número de colunas em uma coleção. int somente leitura.

**Retorno:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Retorna a coluna no índice especificado. [Column](../../com.aspose.slides/column) somente leitura.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Cria uma cópia da linha modelo especificada e a insere no final de uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Coluna usada como modelo. |
| withAttachedColumns | boolean | True para copiar também todas as colunas anexadas à linha modelo. |

**Retorno:**
com.aspose.slides.IColumn[] - Colunas adicionadas.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Cria uma cópia da coluna modelo especificada e a insere na posição especificada em uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da nova coluna. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Coluna usada como modelo. |
| withAttachedColumns | boolean | True para copiar também todas as colunas anexadas à coluna modelo. |

**Retorno:**
com.aspose.slides.IColumn[] - Colunas inseridas.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Remove uma coluna na posição especificada de uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstColumnIndex | int | Índice da coluna a ser excluída. |
| withAttachedRows | boolean | True para excluir também todas as colunas anexadas. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Retorna um enumerador que itera sobre a coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Retorna um iterador java para toda a coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Um java.util.Iterator para toda a coleção.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). boolean somente leitura.

**Retorno:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna a raiz de sincronização. Object somente leitura.

**Retorno:**
java.lang.Object