---
title: CommentCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет собой коллекцию комментариев одного автора.
type: docs
url: /ru/com.aspose.slides/commentcollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Представляет собой коллекцию комментариев одного автора.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество элементов, фактически содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Добавляет новый комментарий в конец коллекции. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Добавляет новый современный комментарий в конец коллекции. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Вставляет новый комментарий в коллекцию по указанному индексу. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Вставляет новый современный комментарий в коллекцию по указанному индексу. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми комментариями. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив со всеми комментариями из указанного диапазона. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Удаляет первое вхождение указанного комментария в коллекции. |
| [clear()](#clear--) | Удаляет все комментарии из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Находит комментарий в коллекции по индексу. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |

### size() {#size--}
```
public final int size()
```

Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения  int .

**Returns:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Возвращает элемент по указанному индексу. Только для чтения [Comment](../../com.aspose.slides/comment).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Добавляет новый комментарий в конец коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст нового комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, где будет добавлен новый комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где будет добавлен новый комментарий. |
| creationTime | java.util.Date | Время создания комментария. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Добавленный комментарий.

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Добавляет новый современный комментарий в конец коллекции.

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


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст нового современного комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, где будет добавлен новый современный комментарий. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура на слайде, к которой привязан новый современный комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где будет добавлен новый современный комментарий. |
| creationTime | java.util.Date | Время создания современного комментария. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Добавленный современный комментарий.

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Вставляет новый комментарий в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента в коллекции, в который следует вставить комментарий. |
| text | java.lang.String | Текст нового комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, где будет добавлен новый комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где будет добавлен новый комментарий. |
| creationTime | java.util.Date | Время создания комментария. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Вставленный комментарий.

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Вставляет новый современный комментарий в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента в коллекции, в который следует вставить современный комментарий. |
| text | java.lang.String | Текст нового современного комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, где будет добавлен новый современный комментарий. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура на слайде, к которой привязан новый современный комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где будет добавлен новый современный комментарий. |
| creationTime | java.util.Date | Время создания современного комментария. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Вставленный современный комментарий.

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Создаёт и возвращает массив со всеми комментариями.

**Returns:**
com.aspose.slides.IComment[] - Массив [Comment](../../com.aspose.slides/comment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Создаёт и возвращает массив со всеми комментариями из указанного диапазона.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первого комментария, который следует вернуть. |
| count | int | Количество комментариев, которые следует вернуть. |

**Returns:**
com.aspose.slides.IComment[] - Массив [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который следует удалить. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Удаляет первое вхождение указанного комментария в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Комментарий, который следует удалить из коллекции. |

### clear() {#clear--}
```
public final void clear()
```

Удаляет все комментарии из коллекции.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Перечислитель IGenericEnumerator, который можно использовать для перебора коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - java.util.Iterator для всей коллекции.

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Находит комментарий в коллекции по индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| idx | int | Уникальный индекс комментария для поиска  int . |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Найденный комментарий или null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения  boolean .

**Returns:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения  Object .

**Returns:**
java.lang.Object