---
title: RowCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de linhas de tabela.
type: docs
url: /pt/com.aspose.slides/rowcollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Representa a coleção de linhas de tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Obtém o número de linhas realmente contidas na coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna a linha no índice especificado. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Remove uma linha na posição especificada de uma tabela. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### size() {#size--}
```
public final int size()
```

Obtém o número de linhas realmente contidas na coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Retorna a linha no índice especificado. Somente leitura [Row](../../com.aspose.slides/row).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Linha que é usada como modelo. |
| withAttachedRows | boolean | True para copiar também todas as linhas anexadas à linha modelo. |

**Retorna:**
com.aspose.slides.IRow[] - Linhas adicionadas.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma nova linha. |
| templ | [IRow](../../com.aspose.slides/irow) | Linha que é usada como modelo. |
| withAttachedRows | boolean | True para copiar também todas as linhas anexadas à linha modelo. |

**Retorna:**
com.aspose.slides.IRow[] - Linhas inseridas.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Remove uma linha na posição especificada de uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstRowIndex | int | Índice de uma linha a ser excluída. |
| withAttachedRows | boolean | True para excluir também todas as linhas anexadas. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Um java.util.Iterator para a coleção inteira.
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

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object