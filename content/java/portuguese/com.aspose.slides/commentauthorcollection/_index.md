---
title: CommentAuthorCollection
second_title: Aspose.Slides para Referência da API Java
description: Representa uma coleção de autores de comentários.
type: docs
url: /pt/com.aspose.slides/commentauthorcollection/
---
**Herança:**  
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**  
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)  
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Representa uma coleção de autores de comentários.
## Métodos

| Method | Description |
| --- | --- |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Adiciona um novo autor ao final de uma coleção. |
| [toArray()](#toArray--) | Cria e retorna um array com todos os autores. |
| [findByName(String name)](#findByName-java.lang.String-) | Encontra autor em uma coleção pelo nome. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Encontra autor em uma coleção pelo nome e iniciais. |
| [removeAt(int index)](#removeAt-int-) | Remove o autor no índice especificado da coleção. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Remove a primeira ocorrência do autor especificado em uma coleção. |
| [clear()](#clear--) | Remove todos os autores de uma coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### size() {#size--}
```
public final int size()
```

Obtém o número de elementos realmente contidos na coleção. int somente leitura.

**Retorno:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Adiciona um novo autor ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome de um novo autor. |
| initials | java.lang.String | Iniciais de um novo autor. |

**Retorno:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Novo [ICommentAuthor](../../com.aspose.slides/icommentauthor) objeto.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Cria e retorna um array com todos os autores.

**Retorno:**
com.aspose.slides.ICommentAuthor[] - Array de [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Encontra autor em uma coleção pelo nome.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome de um autor a ser encontrado. |

**Retorno:**
com.aspose.slides.ICommentAuthor[] - Autor ou nulo.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Encontra autor em uma coleção pelo nome e iniciais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome de um autor a ser encontrado. |
| initials | java.lang.String | Iniciais de um autor a ser encontrado. |

**Retorno:**
com.aspose.slides.ICommentAuthor[] - Autor ou nulo.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o autor no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Remove a primeira ocorrência do autor especificado em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | O autor a ser removido de uma coleção. |
### clear() {#clear--}
```
public final void clear()
```

Remove todos os autores de uma coleção.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Retorna um iterador java para toda a coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Um java.util.Iterator para toda a coleção.
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

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). boolean somente leitura.

**Retorno:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Object somente leitura.

**Retorno:**
java.lang.Object