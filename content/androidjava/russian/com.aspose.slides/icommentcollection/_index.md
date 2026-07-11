---
title: ICommentCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию комментариев одного автора.
type: docs
url: /ru/com.aspose.slides/icommentcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Представляет коллекцию комментариев одного автора.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Добавить новый комментарий в конец коллекции. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Добавить новый современный комментарий в конец коллекции. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Вставить новый комментарий в коллекцию по указанному индексу. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Вставить новый современный комментарий в коллекцию по указанному индексу. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми комментариями. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив со всеми комментариями из указанного диапазона. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Удаляет первое вхождение указанного комментария в коллекции. |
| [clear()](#clear--) | Удаляет все комментарии из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Получает элемент по указанному индексу. Только для чтения [IComment](../../com.aspose.slides/icomment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Добавить новый комментарий в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст нового комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который добавляется новый комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где добавляется новый комментарий. |
| creationTime | java.util.Date | Время создания комментария. |

**Возвращаемое значение:**
[IComment](../../com.aspose.slides/icomment) - Добавленный комментарий.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Добавить новый современный комментарий в конец коллекции.

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
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который добавляется новый современный комментарий. |
| shape | [IShape](../../com.aspose.slides/ishape) | Форма на слайде, к которой привязан новый современный комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где добавляется новый современный комментарий. |
| creationTime | java.util.Date | Время создания современного комментария. |

**Возвращаемое значение:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Добавленный современный комментарий.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Вставить новый комментарий в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента в коллекции, в который следует вставить комментарий. |
| text | java.lang.String | Текст нового комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который добавляется новый комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где добавляется новый комментарий. |
| creationTime | java.util.Date | Время создания комментария. |

**Возвращаемое значение:**
[IComment](../../com.aspose.slides/icomment) - Вставленный комментарий.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Вставить новый современный комментарий в коллекцию по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента в коллекции, в который следует вставить современный комментарий. |
| text | java.lang.String | Текст нового современного комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который добавляется новый современный комментарий. |
| shape | [IShape](../../com.aspose.slides/ishape) | Форма на слайде, к которой привязан новый современный комментарий. |
| position | android.graphics.PointF | Позиция на слайде, где добавляется новый современный комментарий. |
| creationTime | java.util.Date | Время создания современного комментария. |

**Возвращаемое значение:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Вставленный современный комментарий.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Создаёт и возвращает массив со всеми комментариями.

**Возвращаемое значение:**
com.aspose.slides.IComment[] - Массив [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Создаёт и возвращает массив со всеми комментариями из указанного диапазона.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первого комментария для возврата. |
| count | int | Количество комментариев для возврата. |

**Возвращаемое значение:**
com.aspose.slides.IComment[] - Массив [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Удаляет первое вхождение указанного комментария в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Комментарий, который нужно удалить из коллекции. |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все комментарии из коллекции.