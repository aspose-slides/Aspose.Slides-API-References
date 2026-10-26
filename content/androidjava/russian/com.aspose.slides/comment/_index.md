---
title: Comment
second_title: Aspose.Slides для Android через Java: справочник API
description: Представляет комментарий на слайде.
type: docs
url: /ru/com.aspose.slides/comment/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Представляет комментарий на слайде.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Создает экземпляр класса Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Добавляет пустой слайд
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Добавляет автора
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Устанавливает позицию для комментариев
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Добавляет комментарий к слайду для автора на слайде 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Добавляет комментарий к слайду для автора на слайде 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Сохраняет файл презентации PowerPoint
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Создает экземпляр класса Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Перебирает CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Перебирает Comments
>          for (IComment comment1 : author.getComments())
>          {
>              Comment comment = (Comment) comment1;
>              System.out.println("ISlide :" + comment.getSlide().getSlideNumber() + " has comment: " + comment.getText() + " with Author: " + comment.getAuthor().getName() + " posted on time :" + comment.getCreatedTime().toString() + "\n");
>          }
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to add comments and get replies to them.
>  
>  // Создает экземпляр класса Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Добавляет комментарий
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Добавляет ответ к comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Добавляет еще один ответ к comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Добавляет ответ к существующему ответу
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Отображает иерархию комментариев в консоли
>      ISlide slide = pres.getSlides().get_Item(0);
>      IComment[] comments = slide.getSlideComments(null);
>      for (int i = 0; i < comments.length; i++)
>      {
>          IComment comment = comments[i];
>          while (comment.getParentComment() != null)
>          {
>              System.out.println("\t");
>              comment = comment.getParentComment();
>          }
>          System.out.println(comments[i].getAuthor().getName() + " : " + comments[i].getText());
>      }
>      pres.save("parent_comment.pptx",SaveFormat.Pptx);
>      // Удаляет comment1 и все ответы на него
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) | Возвращает или задает простой текст комментария к слайду. |
| [setText(String value)](#setText-java.lang.String-) | Возвращает или задает простой текст комментария к слайду. |
| [getCreatedTime()](#getCreatedTime--) | Возвращает или задает время создания комментария. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Возвращает или задает время создания комментария. |
| [getSlide()](#getSlide--) | Возвращает или задает родительский слайд комментария. |
| [getAuthor()](#getAuthor--) | Возвращает автора комментария. |
| [getPosition()](#getPosition--) | Возвращает или задает позицию комментария на слайде. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Возвращает или задает позицию комментария на слайде. |
| [remove()](#remove--) | Удаляет комментарий и все его ответы из родительской коллекции. |
| [getParentComment()](#getParentComment--) | Получает или задает родительский комментарий. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Получает или задает родительский комментарий. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Возвращает или задает простой текст комментария к слайду. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Возвращает или задает простой текст комментария к слайду. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Возвращает или задает время создания комментария. Установка этого свойства в java.util.Date(Long.MIN_VALUE) означает, что время комментария не задано. Чтение/запись java.util.Date.

--------------------

Время комментария является необязательным параметром.

**Возвращаемое значение:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Возвращает или задает время создания комментария. Установка этого свойства в java.util.Date(Long.MIN_VALUE) означает, что время комментария не задано. Чтение/запись java.util.Date.

--------------------

Время комментария является необязательным параметром.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Возвращает или задает родительский слайд комментария. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Возвращает автора комментария. Только для чтения [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Возвращаемое значение:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Возвращает или задает позицию комментария на слайде. Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Возвращает или задает позицию комментария на слайде. Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

Удаляет комментарий и все его ответы из родительской коллекции.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Получает или задает родительский комментарий. Чтение/запись [IComment](../../com.aspose.slides/icomment).

**Возвращаемое значение:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Получает или задает родительский комментарий. Чтение/запись [IComment](../../com.aspose.slides/icomment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject