---
title: AddModernComment
second_title: Справочник по API Aspose.Slides для .NET
description: Добавить новый современный комментарий в конец коллекции.
type: docs
weight: 30
url: /ru/net/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection.AddModernComment method

Добавить новый современный комментарий в конец коллекции.

```csharp
public IModernComment AddModernComment(string text, ISlide slide, IShape shape, PointF position, 
    DateTime creationTime)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Простой текст нового современного комментария. |
| слайд | ISlide | Слайд в презентации, куда добавить новый современный комментарий. |
| shape | IShape | Фигура на слайде, с которой связан новый современный комментарий. |
| position | PointF | Позиция на слайде, куда добавить новый современный комментарий. |
| creationTime | DateTime | Время создания современного комментария. |

### Возвращаемое значение

Добавлен современный комментарий.

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ICommentAuthor newAuthor = pres.CommentAuthors.AddAuthor("Some Author", "SA");
    newAuthor.Comments.AddModernComment("This is modern comment", pres.Slides[0], null, new PointF(100, 100), DateTime.Now);

    pres.Save(outPptxFileName, SaveFormat.Pptx);
}
```

### Смотрите также

* interface [IModernComment](../../imoderncomment)
* interface [ISlide](../../islide)
* interface [IShape](../../ishape)
* interface [ICommentCollection](../../icommentcollection)
* пространство имен [Aspose.Slides](../../icommentcollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->