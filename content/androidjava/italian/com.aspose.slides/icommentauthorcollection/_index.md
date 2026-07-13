---
title: ICommentAuthorCollection
second_title: Aspose.Slides per Android tramite il riferimento API Java
description: Rappresenta una raccolta di autori di commenti.
type: docs
url: /it/com.aspose.slides/icommentauthorcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Rappresenta una raccolta di autori di commenti.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Aggiunge un nuovo autore alla fine di una raccolta. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutti gli autori. |
| [findByName(String name)](#findByName-java.lang.String-) | Trova l'autore in una raccolta per nome. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Trova l'autore in una raccolta per nome e iniziali. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'autore all'indice specificato della raccolta. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Rimuove la prima occorrenza dell'autore specificato in una raccolta. |
| [clear()](#clear--) | Rimuove tutti gli autori da una raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

Ottiene l'elemento all'indice specificato. **Solo lettura** [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

Aggiunge un nuovo autore alla fine di una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome del nuovo autore. |
| initials | java.lang.String | Iniziali del nuovo autore. |

**Restituisce:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nuovo oggetto [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Crea e restituisce un array con tutti gli autori.

**Restituisce:**
com.aspose.slides.ICommentAuthor[] - Array di [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Trova l'autore in una raccolta per nome.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'autore da trovare. |

**Restituisce:**
com.aspose.slides.ICommentAuthor[] - Autore o null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Trova l'autore in una raccolta per nome e iniziali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome dell'autore da trovare. |
| initials | java.lang.String | Iniziali dell'autore da trovare. |

**Restituisce:**
com.aspose.slides.ICommentAuthor[] - Autore o null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'autore all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Rimuove la prima occorrenza dell'autore specificato in una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | L'autore da rimuovere dalla raccolta. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti gli autori da una raccolta.