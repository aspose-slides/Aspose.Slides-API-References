---
title: ICommentAuthorCollection
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji Java API
description: Reprezentuje kolekcję autorów komentarzy.
type: docs
url: /pl/com.aspose.slides/icommentauthorcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Reprezentuje kolekcję autorów komentarzy.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Dodaje nowego autora na końcu kolekcji. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi autorami. |
| [findByName(String name)](#findByName-java.lang.String-) | Znajduje autora w kolekcji po nazwie. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Znajduje autora w kolekcji po nazwie i inicjałach. |
| [removeAt(int index)](#removeAt-int-) | Usuwa autora pod określonym indeksem w kolekcji. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Usuwa pierwsze wystąpienie określonego autora w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkich autorów z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

Pobiera element pod określonym indeksem. Tylko do odczytu [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

Dodaje nowego autora na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa nowego autora. |
| initials | java.lang.String | Inicjały nowego autora. |

**Zwraca:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nowy [ICommentAuthor](../../com.aspose.slides/icommentauthor) obiekt.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Tworzy i zwraca tablicę ze wszystkimi autorami.

**Zwraca:**
com.aspose.slides.ICommentAuthor[] - Tablica [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Znajduje autora w kolekcji po nazwie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa autora do znalezienia. |

**Zwraca:**
com.aspose.slides.ICommentAuthor[] - Autor lub null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Znajduje autora w kolekcji po nazwie i inicjałach.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa autora do znalezienia. |
| initials | java.lang.String | Inicjały autora do znalezienia. |

**Zwraca:**
com.aspose.slides.ICommentAuthor[] - Autor lub null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa autora pod określonym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Usuwa pierwsze wystąpienie określonego autora w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor do usunięcia z kolekcji. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkich autorów z kolekcji.