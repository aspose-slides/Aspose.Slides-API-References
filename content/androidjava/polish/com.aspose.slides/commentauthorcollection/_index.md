---
title: CommentAuthorCollection
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję autorów komentarzy.
type: docs
url: /pl/com.aspose.slides/commentauthorcollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Represents a collection of comment authors.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o określonym indeksie. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Dodaje nowego autora na końcu kolekcji. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi autorami. |
| [findByName(String name)](#findByName-java.lang.String-) | Znajduje autora w kolekcji po nazwie. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Znajduje autora w kolekcji po nazwie i inicjałach. |
| [removeAt(int index)](#removeAt-int-) | Usuwa autora o określonym indeksie w kolekcji. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Usuwa pierwsze wystąpienie określonego autora w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkich autorów z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### size() {#size--}
```
public final int size()
```


Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


Zwraca element o określonym indeksie. Tylko do odczytu [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```


Dodaje nowego autora na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa nowego autora. |
| initials | java.lang.String | Inicjały nowego autora. |

**Zwraca:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nowy [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


Tworzy i zwraca tablicę ze wszystkimi autorami.

**Zwraca:**
com.aspose.slides.ICommentAuthor[] - Tablica [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
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
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
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
public final void removeAt(int index)
```


Usuwa autora o określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu do usunięcia (liczony od zera). |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Usuwa pierwsze wystąpienie określonego autora w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor do usunięcia z kolekcji. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkich autorów z kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - IGenericEnumerator, który może być używany do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object