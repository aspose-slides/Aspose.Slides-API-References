---
title: CommentAuthorCollection
second_title: Aspose.Slides per Android tramite API di riferimento Java
description: Rappresenta una raccolta di autori di commenti.
type: docs
url: /it/com.aspose.slides/commentauthorcollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Rappresenta una raccolta di autori di commenti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Aggiunge un nuovo autore alla fine di una raccolta. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti gli autori. |
| [findByName(String name)](#findByName-java.lang.String-) | Trova l'autore in una raccolta per nome. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Trova l'autore in una raccolta per nome e iniziali. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'autore all'indice specificato della raccolta. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Rimuove la prima occorrenza dell'autore specificato in una raccolta. |
| [clear()](#clear--) | Rimuove tutti gli autori da una raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che scorre la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Solo lettura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Aggiunge un nuovo autore alla fine di una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome di un nuovo autore. |
| initials | java.lang.String | Iniziali di un nuovo autore. |

**Restituisce:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nuovo oggetto [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Crea e restituisce un array con tutti gli autori.

**Restituisce:**
com.aspose.slides.ICommentAuthor[] - Array di [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Trova l'autore in una raccolta per nome.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome di un autore da trovare. |

**Restituisce:**
com.aspose.slides.ICommentAuthor[] - Autore o null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Trova l'autore in una raccolta per nome e iniziali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome di un autore da trovare. |
| initials | java.lang.String | Iniziali di un autore da trovare. |

**Restituisce:**
com.aspose.slides.ICommentAuthor[] - Autore o null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'autore all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base-zero dell'elemento da rimuovere. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Rimuove la prima occorrenza dell'autore specificato in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | L'autore da rimuovere dalla raccolta. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli autori da una raccolta.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Restituisce un enumeratore che scorre la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Un IGenericEnumerator che può essere usato per scorrere la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Un java.util.Iterator per l'intera raccolta.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object