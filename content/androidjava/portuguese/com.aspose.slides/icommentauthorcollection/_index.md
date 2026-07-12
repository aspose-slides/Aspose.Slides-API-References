---
title: ICommentAuthorCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de autores de comentários.
type: docs
url: /pt/com.aspose.slides/icommentauthorcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Representa uma coleção de autores de comentários.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Adiciona um novo autor ao final de uma coleção. |
| [toArray()](#toArray--) | Cria e retorna um array com todos os autores. |
| [findByName(String name)](#findByName-java.lang.String-) | Encontra o autor em uma coleção pelo nome. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Encontra o autor em uma coleção pelo nome e iniciais. |
| [removeAt(int index)](#removeAt-int-) | Remove o autor no índice especificado da coleção. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Remove a primeira ocorrência do autor especificado em uma coleção. |
| [clear()](#clear--) | Remove todos os autores de uma coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Obtém o elemento no índice especificado. Somente leitura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Adiciona um novo autor ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome de um novo autor. |
| initials | java.lang.String | Iniciais de um novo autor. |

**Retorna:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Novo objeto [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Cria e retorna um array com todos os autores.

**Retorna:**
com.aspose.slides.ICommentAuthor[] - Array de [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Encontra autor em uma coleção pelo nome.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome de um autor a ser encontrado. |

**Retorna:**
com.aspose.slides.ICommentAuthor[] - Autor ou null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Encontra autor em uma coleção pelo nome e iniciais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome de um autor a ser encontrado. |
| initials | java.lang.String | Iniciais de um autor a ser encontrado. |

**Retorna:**
com.aspose.slides.ICommentAuthor[] - Autor ou null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove o autor no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Remove a primeira ocorrência do autor especificado em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | O autor a ser removido de uma coleção. |

### clear() {#clear--}
```
public abstract void clear()
```


Remove todos os autores de uma coleção.