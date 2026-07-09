---
title: Comment
second_title: Aspose.Slides för .NET API-referens
description: Representerar en kommentar på en bild.
type: docs
weight: 2620
url: /sv/aspose.slides/comment/
---
## Comment klass

Representerar en kommentar på en bild.

```csharp
public class Comment : IComment
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Returnerar författaren till en kommentar. Skrivskyddad [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Returnerar eller anger tiden för en kommentarskapning. Att sätta denna egenskap till MinValue betyder att ingen kommentarstid är angiven. Läs/skriv DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Hämtar eller anger föräldrakommentar. Läs/skriv [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Returnerar eller anger positionen för en kommentar på en bild. Läs/skriv PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Returnerar eller anger föräldrabilden för en kommentar. Skrivskyddad [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Returnerar eller anger den rena texten för en bildkommentar. Läs/skriv String. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Tar bort kommentaren och alla dess svar från den föräldrakollektionen. |

### Exempel

Detta exempel visar hur du lägger till en kommentar på en bild i en PowerPoint-presentation.

```csharp
[C#]
// Instansierar Presentation-klassen
using (Presentation presentation = new Presentation())
{
    // Lägger till en tom bild
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Lägger till en författare
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Anger positionen för kommentarer
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Lägger till en bildkommentar för en författare på bild 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Lägger till en bildkommentar för en författare på bild 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Sparar PowerPoint-presentationfilen
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Detta exempel visar hur du får åtkomst till en befintlig kommentar på en bild i en PowerPoint-presentation.

```csharp
[C#]
// Instansierar Presentation-klassen
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Iterera CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Iterera Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Detta exempel visar hur du lägger till kommentarer och hämtar svar på dem.

```csharp
[C#]
// Instansierar Presentation-klassen
using (Presentation pres = new Presentation())
{
    // Lägger till en kommentar
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Lägger till ett svar till comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Lägger till ytterligare ett svar till comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Lägger till ett svar till befintligt svar
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Visar kommentarhierarkin i konsolen
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
    // Tar bort comment1 och alla svar på den
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [IComment](../icomment)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->