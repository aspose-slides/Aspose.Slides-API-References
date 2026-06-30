---
title: Comment
second_title: Aspose.Sildes dla .NET Referencja API
description: Reprezentuje komentarz na slajdzie.
type: docs
weight: 2600
url: /pl/aspose.slides/comment/
---
## Klasa Comment

Reprezentuje komentarz na slajdzie.

```csharp
public class Comment : IComment
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Zwraca autora komentarza. Tylko do odczytu [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Zwraca lub ustawia czas utworzenia komentarza. Ustawienie tej właściwości na MinValue oznacza, że nie ustawiono czasu komentarza. Odczyt/zapis DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Zwraca lub ustawia nadrzędny komentarz. Odczyt/zapis [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Zwraca lub ustawia pozycję komentarza na slajdzie. Odczyt/zapis PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Zwraca lub ustawia slajd nadrzędny komentarza. Tylko do odczytu [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Zwraca lub ustawia zwykły tekst komentarza na slajdzie. Odczyt/zapis String. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Usuwa komentarz i wszystkie jego odpowiedzi z kolekcji nadrzędnej. |

### Przykłady

Ten przykład pokazuje, jak dodać komentarz do slajdu w prezentacji PowerPoint.

```csharp
[C#]
// Tworzy instancję klasy Presentation
using (Presentation presentation = new Presentation())
{
    // Dodaje pusty slajd
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Dodaje autora
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Ustawia pozycję komentarzy
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Dodaje komentarz slajdu dla autora na slajdzie 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Dodaje komentarz slajdu dla autora na slajdzie 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Zapisuje plik prezentacji PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Ten przykład pokazuje, jak uzyskać dostęp do istniejącego komentarza na slajdzie w prezentacji PowerPoint.

```csharp
[C#]
// Tworzy instancję klasy Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Iteruj po autorach komentarzy
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Iteruj po komentarzach
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Ten przykład pokazuje, jak dodać komentarze i uzyskać odpowiedzi na nie.

```csharp
[C#]
// Tworzy instancję klasy Presentation
using (Presentation pres = new Presentation())
{
    // Dodaje komentarz
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Dodaje odpowiedź do comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Dodaje kolejną odpowiedź do comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Dodaje odpowiedź do istniejącej odpowiedzi
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Wyświetla hierarchię komentarzy w konsoli
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
    // Usuwa comment1 i wszystkie odpowiedzi do niego
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [IComment](../icomment)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->