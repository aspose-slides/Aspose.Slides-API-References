---
title: ICommentCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolekcję komentarzy jednego autora.
type: docs
url: /pl/com.aspose.slides/icommentcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Reprezentuje kolekcję komentarzy jednego autora.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Dodaje nowy komentarz na końcu kolekcji. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Dodaje nowy nowoczesny komentarz na końcu kolekcji. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Wstawia nowy komentarz do kolekcji pod określonym indeksem. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi komentarzami. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę ze wszystkimi komentarzami z określonego zakresu. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem w kolekcji. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Usuwa pierwsze wystąpienie określonego komentarza w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie komentarze z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Pobiera element pod określonym indeksem. Tylko do odczytu [IComment](../../com.aspose.slides/icomment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Dodaje nowy komentarz na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Czysty tekst nowego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy komentarz. |
| creationTime | java.util.Date | Czas utworzenia komentarza. |

**Zwraca:**
[IComment](../../com.aspose.slides/icomment) - Dodany komentarz.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
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
| text | java.lang.String | Czysty tekst nowego nowoczesnego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy nowoczesny komentarz. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt na slajdzie, z którym powiązany jest nowy nowoczesny komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy nowoczesny komentarz. |
| creationTime | java.util.Date | Czas utworzenia nowoczesnego komentarza. |

**Zwraca:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Dodany nowoczesny komentarz.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Wstawia nowy komentarz do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu w kolekcji, pod którym należy wstawić komentarz. |
| text | java.lang.String | Czysty tekst nowego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy komentarz. |
| creationTime | java.util.Date | Czas utworzenia komentarza. |

**Zwraca:**
[IComment](../../com.aspose.slides/icomment) - Wstawiony komentarz.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Wstawia nowy nowoczesny komentarz do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu w kolekcji, pod którym należy wstawić nowoczesny komentarz. |
| text | java.lang.String | Czysty tekst nowego nowoczesnego komentarza. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd w prezentacji, w którym dodać nowy nowoczesny komentarz. |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt na slajdzie, z którym powiązany jest nowy nowoczesny komentarz. |
| position | android.graphics.PointF | Pozycja na slajdzie, w której dodać nowy nowoczesny komentarz. |
| creationTime | java.util.Date | Czas utworzenia nowoczesnego komentarza. |

**Zwraca:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Wstawiony nowoczesny komentarz.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Tworzy i zwraca tablicę ze wszystkimi komentarzami.

**Zwraca:**
com.aspose.slides.IComment[] - Tablica [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Tworzy i zwraca tablicę ze wszystkimi komentarzami z określonego zakresu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego komentarza do zwrócenia. |
| count | int | Liczba komentarzy do zwrócenia. |

**Zwraca:**
com.aspose.slides.IComment[] - Tablica [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa element pod określonym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Usuwa pierwsze wystąpienie określonego komentarza w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Komentarz do usunięcia z kolekcji. |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie komentarze z kolekcji.