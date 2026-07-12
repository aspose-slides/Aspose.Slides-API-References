---
title: CommentAuthorCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de autores de comentarios.
type: docs
url: /es/com.aspose.slides/commentauthorcollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Representa una colección de autores de comentarios.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Agrega un nuevo autor al final de la colección. |
| [toArray()](#toArray--) | Crea y devuelve una matriz con todos los autores. |
| [findByName(String name)](#findByName-java.lang.String-) | Encuentra el autor en una colección por nombre. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Encuentra el autor en una colección por nombre e iniciales. |
| [removeAt(int index)](#removeAt-int-) | Elimina el autor en el índice especificado de la colección. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Elimina la primera aparición del autor especificado en una colección. |
| [clear()](#clear--) | Elimina todos los autores de una colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al arreglo especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve la raíz de sincronización. |
### size() {#size--}
```
public final int size()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
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
public final ICommentAuthor addAuthor(String name, String initials)
```

Agrega un nuevo autor al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre del nuevo autor. |
| initials | java.lang.String | Iniciales del nuevo autor. |

**Devuelve:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nuevo objeto [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Crea y devuelve una matriz con todos los autores.

**Devuelve:**
com.aspose.slides.ICommentAuthor[] - Matriz de [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Encuentra el autor en una colección por nombre.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre del autor a buscar. |

**Devuelve:**
com.aspose.slides.ICommentAuthor[] - Autor o null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Encuentra el autor en una colección por nombre e iniciales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre del autor a buscar. |
| initials | java.lang.String | Iniciales del autor a buscar. |

**Devuelve:**
com.aspose.slides.ICommentAuthor[] - Autor o null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el autor en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Elimina la primera aparición del autor especificado en una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | El autor a eliminar de la colección. |
### clear() {#clear--}
```
public final void clear()
```

Elimina todos los autores de una colección.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Un java.util.Iterator para toda la colección.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al arreglo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Arreglo de destino. |
| index | int | Índice inicial en el arreglo de destino. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). Solo lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object