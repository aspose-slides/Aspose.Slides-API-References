---
title: ICommentCollection
second_title: Справочник API Aspose.Slides для Java
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

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Добавляет новый комментарий в конец коллекции. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Добавляет новый современный комментарий в конец коллекции. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Вставляет новый комментарий в коллекцию по указанному индексу. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Вставляет новый современный комментарий в коллекцию по указанному индексу. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми комментариями. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив с комментариями из указанного диапазона. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Удаляет первое вхождение указанного комментария в коллекции. |
| [clear()](#clear--) | Удаляет все комментарии из коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IComment](../../com.aspose.slides/icomment).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Добавляет новый комментарий в конец коллекции.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Обычный текст нового комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который следует добавить новый комментарий. |
| position | java.awt.geom.Point2D.Float | Позиция на слайде, где добавить новый комментарий. |
| creationTime | java.util.Date | Время создания комментария. |

**Возвращаемое значение:**
[IComment](../../com.aspose.slides/icomment) - Добавленный комментарий.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Добавляет новый современный комментарий в конец коллекции.

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


**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Обычный текст нового современного комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который следует добавить новый современный комментарий. |
| shape | [IShape](../../com.aspose.slides/ishape) | Форма на слайде, к которой привязан новый современный комментарий. |
| position | java.awt.geom.Point2D.Float | Позиция на слайде, где добавить новый современный комментарий. |
| creationTime | java.util.Date | Время создания современного комментария. |

**Возвращаемое значение:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Добавленный современный комментарий.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Вставляет новый комментарий в коллекцию по указанному индексу.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Индекс элемента в коллекции, в который следует вставить комментарий. |
| text | java.lang.String | Обычный текст нового комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который следует добавить новый комментарий. |
| position | java.awt.geom.Point2D.Float | Позиция на слайде, где добавить новый комментарий. |
| creationTime | java.util.Date | Время создания комментария. |

**Возвращаемое значение:**
[IComment](../../com.aspose.slides/icomment) - Вставленный комментарий.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Вставляет новый современный комментарий в коллекцию по указанному индексу.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Индекс элемента в коллекции, в который следует вставить современный комментарий. |
| text | java.lang.String | Обычный текст нового современного комментария. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд в презентации, в который следует добавить новый современный комментарий. |
| shape | [IShape](../../com.aspose.slides/ishape) | Форма на слайде, к которой привязан новый современный комментарий. |
| position | java.awt.geom.Point2D.Float | Позиция на слайде, где добавить новый современный комментарий. |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который нужно удалить. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Удаляет первое вхождение указанного комментария в коллекции.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Комментарий, который необходимо удалить из коллекции. |
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все комментарии из коллекции.