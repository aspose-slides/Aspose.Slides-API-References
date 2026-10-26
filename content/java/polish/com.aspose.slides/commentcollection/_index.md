---
title: CommentCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kolekcję komentarzy jednego autora.
type: docs
url: /pl/com.aspose.slides/commentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Reprezentuje kolekcję komentarzy jednego autora.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę elementów rzeczywiście znajdujących się w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o określonym indeksie. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Dodaje nowy komentarz na koniec kolekcji. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Dodaje nowy nowoczesny komentarz na koniec kolekcji. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Wstawia nowy komentarz do kolekcji pod określonym indeksem. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi komentarzami. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę z komentarzami z określonego zakresu. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o określonym indeksie w kolekcji. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Usuwa pierwsze wystąpienie określonego komentarza w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie komentarze z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Znajduje komentarz w kolekcji po indeksie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (bezpieczny wątkowo). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca obiekt bazowy synchronizacji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów rzeczywiście znajdujących się w kolekcji. Tylko do odczytu int .

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Zwraca element o określonym indeksie. Tylko do odczytu [Comment](../../com.aspose.slides/comment).

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Dodaje nowy komentarz na koniec kolekcji.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Zwykły tekst nowego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy komentarz. |
| position | java.awt.geom.Point2D.Float | Pozycja na slajdzie, w którym dodać nowy komentarz. |
| creationTime | java.util.Date | Czas utworzenia komentarza. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Dodany komentarz.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Dodaje nowy nowoczesny komentarz na koniec kolekcji.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Zwykły tekst nowego nowoczesnego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy nowoczesny komentarz. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt na slajdzie, z którym powiązany jest nowy nowoczesny komentarz. |
| position | java.awt.geom.Point2D.Float | Pozycja na slajdzie, w którym dodać nowy nowoczesny komentarz. |
| creationTime | java.util.Date | Czas utworzenia nowoczesnego komentarza. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Dodany nowoczesny komentarz.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Wstawia nowy komentarz do kolekcji pod określonym indeksem.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu w kolekcji, pod którym komentarz ma być wstawiony. |
| text | java.lang.String | Zwykły tekst nowego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy komentarz. |
| position | java.awt.geom.Point2D.Float | Pozycja na slajdzie, w którym dodać nowy komentarz. |
| creationTime | java.util.Date | Czas utworzenia komentarza. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Wstawiony komentarz.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu w kolekcji, pod którym nowoczesny komentarz ma być wstawiony. |
| text | java.lang.String | Zwykły tekst nowego nowoczesnego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy nowoczesny komentarz. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt na slajdzie, z którym powiązany jest nowy nowoczesny komentarz. |
| position | java.awt.geom.Point2D.Float | Pozycja na slajdzie, w którym dodać nowy nowoczesny komentarz. |
| creationTime | java.util.Date | Czas utworzenia nowoczesnego komentarza. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Wstawiony nowoczesny komentarz.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Tworzy i zwraca tablicę ze wszystkimi komentarzami.

**Returns:**
com.aspose.slides.IComment[] - Tablica [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę z komentarzami z określonego zakresu.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego komentarza do zwrócenia. |
| count | int | Liczba komentarzy do zwrócenia. |

**Returns:**
com.aspose.slides.IComment[] - Tablica [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element o określonym indeksie w kolekcji.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Usuwa pierwsze wystąpienie określonego komentarza w kolekcji.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Komentarz do usunięcia z kolekcji. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie komentarze z kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - java.util.Iterator dla całej kolekcji.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Znajduje komentarz w kolekcji po indeksie.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| idx | int | Unikalny indeks komentarza do znalezienia  int . |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Znaleziony komentarz lub null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Indeks początkowy w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (bezpieczny wątkowo). Tylko do odczytu boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca obiekt bazowy synchronizacji. Tylko do odczytu Object .

**Returns:**
java.lang.Object