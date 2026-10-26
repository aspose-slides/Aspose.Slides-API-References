---
title: ICommentAuthorCollection
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una colección de autores de comentarios.
type: docs
url: /es/com.aspose.slides/icommentauthorcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Representa una colección de autores de comentarios.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Agrega nuevo autor al final de la colección. |
| [toArray()](#toArray--) | Crea y devuelve una matriz con todos los autores. |
| [findByName(String name)](#findByName-java.lang.String-) | Busca autor en una colección por nombre. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Busca autor en una colección por nombre e iniciales. |
| [removeAt(int index)](#removeAt-int-) | Elimina al autor en el índice especificado de la colección. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Elimina la primera ocurrencia del autor especificado en una colección. |
| [clear()](#clear--) | Elimina todos los autores de una colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

Agrega nuevo autor al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre del nuevo autor. |
| initials | java.lang.String | Iniciales del nuevo autor. |

**Devuelve:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nuevo [ICommentAuthor](../../com.aspose.slides/icommentauthor) objeto.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Crea y devuelve una matriz con todos los autores.

**Devuelve:**
com.aspose.slides.ICommentAuthor[] - Matriz de [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Busca autor en una colección por nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre del autor a buscar. |

**Devuelve:**
com.aspose.slides.ICommentAuthor[] - Autor o null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Busca autor en una colección por nombre e iniciales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre del autor a buscar. |
| initials | java.lang.String | Iniciales del autor a buscar. |

**Devuelve:**
com.aspose.slides.ICommentAuthor[] - Autor o null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina al autor en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Elimina la primera ocurrencia del autor especificado en una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | El autor a eliminar de la colección. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los autores de una colección.