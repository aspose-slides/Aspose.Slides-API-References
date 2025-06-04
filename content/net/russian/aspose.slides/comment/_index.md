---
title: Comment
second_title: Aspose.Sildes для .NET API Reference
description: Представляет комментарий на слайде.
type: docs
weight: 2530
url: /ru/aspose.slides/comment/
---

## Comment class

Представляет комментарий на слайде.

```csharp
public class Comment : IComment
```

## Properties

| Name | Description |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Возвращает автора комментария. Только для чтения [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Возвращает или задает время создания комментария. Установка этого свойства в MinValue означает, что время комментария не установлено. Чтение/запись DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Получает или задает родительский комментарий. Чтение/запись [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Возвращает или задает позицию комментария на слайде. Чтение/запись PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Возвращает или задает родительский слайд комментария. Только для чтения [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Возвращает или задает текст комментария на слайде. Чтение/запись String. |

## Methods

| Name | Description |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Удаляет комментарий и все его ответы из родительской коллекции. |

### Examples

Этот пример показывает, как добавить комментарий на слайд в презентации PowerPoint.

```csharp
[C#]
// Создает экземпляр класса Presentation
using (Presentation presentation = new Presentation())
{
    // Добавляет пустой слайд
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Добавляет автора
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Устанавливает позицию для комментариев
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Добавляет комментарий к слайду для автора на слайде 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Добавляет комментарий к слайду для автора на слайде 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Сохраняет файл PowerPoint Presentation
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Этот пример показывает, как получить доступ к существующему комментарию на слайде в презентации PowerPoint.

```csharp
[C#]
// Создает экземпляр класса Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Перебирает CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Перебирает Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Этот пример показывает, как добавлять комментарии и получать на них ответы.

```csharp
[C#]
// Создает экземпляр класса Presentation
using (Presentation pres = new Presentation())
{
    // Добавляет комментарий
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Добавляет ответ на comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Добавляет еще один ответ на comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Добавляет ответ на существующий ответ
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Отображает иерархию комментариев в консоли
    ISlide slide = pres.Slides[0];
    var comments = slide.GetSlideComments(null);
    for (int i = 0; i < comments.Length; i++)
    {
        IComment comment = comments[i];
        while (comment.ParentComment != null)
        {
            Console.Write("\t");
            comment = comment.ParentComment;
        }
        Console.Write("{0} : {1}", comments[i].Author.Name, comments[i].Text);
        Console.WriteLine();
    }
    pres.Save("parent_comment.pptx",SaveFormat.Pptx);
    // Удаляет comment1 и все ответы на него
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IComment](../icomment)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->