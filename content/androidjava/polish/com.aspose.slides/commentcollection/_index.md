---
title: CommentCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolekcję komentarzy jednego autora.
type: docs
url: /pl/com.aspose.slides/commentcollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Reprezentuje kolekcję komentarzy jednego autora.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Pobiera liczbę elementów faktycznie znajdujących się w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o określonym indeksie. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Dodaje nowy komentarz na końcu kolekcji. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Dodaje nowy nowoczesny komentarz na końcu kolekcji. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Wstawia nowy komentarz do kolekcji pod określonym indeksem. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi komentarzami. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę ze wszystkimi komentarzami z podanego zakresu. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o określonym indeksie w kolekcji. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Usuwa pierwsze wystąpienie określonego komentarza w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie komentarze z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Znajduje komentarz w kolekcji po indeksie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |

### size() {#size--}
```
public final int size()
```

Pobiera liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu  int .

**Zwraca:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Pobiera element o określonym indeksie. Tylko do odczytu [Comment](../../com.aspose.slides/comment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Dodaje nowy komentarz na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Zwykły tekst nowego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy komentarz. |
| creationTime | java.util.Date | Czas utworzenia komentarza. |

**Zwraca:**
[IComment](../../com.aspose.slides/icomment) - Dodany komentarz.

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Dodaje nowy nowoczesny komentarz na końcu kolekcji.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Zwykły tekst nowego nowoczesnego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy nowoczesny komentarz. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt na slajdzie, do którego powiązany jest nowy nowoczesny komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy nowoczesny komentarz. |
| creationTime | java.util.Date | Czas utworzenia nowoczesnego komentarza. |

**Zwraca:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Dodany nowoczesny komentarz.

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Wstawia nowy komentarz do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu w kolekcji, pod którym należy wstawić komentarz. |
| text | java.lang.String | Zwykły tekst nowego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy komentarz. |
| creationTime | java.util.Date | Czas utworzenia komentarza. |

**Zwraca:**
[IComment](../../com.aspose.slides/icomment) - Wstawiony komentarz.

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu w kolekcji, pod którym należy wstawić nowoczesny komentarz. |
| text | java.lang.String | Zwykły tekst nowego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy nowoczesny komentarz. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt na slajdzie, do którego powiązany jest nowy nowoczesny komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy nowoczesny komentarz. |
| creationTime | java.util.Date | Czas utworzenia komentarza. |

**Zwraca:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Wstawiony nowoczesny komentarz.

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Tworzy i zwraca tablicę ze wszystkimi komentarzami.

**Zwraca:**
com.aspose.slides.IComment[] - Tablica [Comment](../../com.aspose.slides/comment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę ze wszystkimi komentarzami z określonego zakresu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego komentarza do zwrócenia. |
| count | int | Liczba komentarzy do zwrócenia. |

**Zwraca:**
com.aspose.slides.IComment[] - Tablica [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element o określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Usuwa pierwsze wystąpienie określonego komentarza w kolekcji.

**Parametry:**
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

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - java.util.Iterator dla całej kolekcji.

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Znajduje komentarz w kolekcji po indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| idx | int | Unikalny indeks komentarza do znalezienia  int . |

**Zwraca:**
[IComment](../../com.aspose.slides/icomment) - Znaleziony komentarz lub null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Indeks początkowy w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu  boolean .

**Zwraca:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu  Object .

**Zwraca:**
java.lang.Object