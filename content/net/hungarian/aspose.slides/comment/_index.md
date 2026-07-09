---
title: Comment
second_title: Aspose.Sildes a .NET API Referenciája
description: Egy dián lévő megjegyzést ábrázol.
type: docs
weight: 2620
url: /hu/aspose.slides/comment/
---
## Comment osztály

Egy dián lévő megjegyzést reprezentál.

```csharp
public class Comment : IComment
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Visszaadja a megjegyzés szerzőjét. Csak olvasható [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Visszaadja vagy beállítja a megjegyzés létrehozásának idejét. Ennek a tulajdonságnak MinValue értékre állítása azt jelenti, hogy nincs beállítva megjegyzés idő. Olvasás/írás DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Visszaadja vagy beállítja a szülő megjegyzést. Olvasás/írás [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Visszaadja vagy beállítja egy megjegyzés pozícióját a dián. Olvasás/írás PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Visszaadja vagy beállítja a megjegyzés szülő diáját. Csak olvasható [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Visszaadja vagy beállítja a diamegjegyzés egyszerű szövegét. Olvasás/írás String. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Eltávolítja a megjegyzést és annak összes válaszát a szülőgyűjteményből. |

### Példák

Ez a példa megmutatja, hogyan adhat megjegyzést egy diára egy PowerPoint prezentációban.

```csharp
[C#]
// Példányosítja a Presentation osztályt
using (Presentation presentation = new Presentation())
{
    // Üres diát ad hozzá
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Szerzőt ad hozzá
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Beállítja a megjegyzések pozícióját
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Megjegyzést ad egy szerzőnek az 1. diára
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Megjegyzést ad egy szerzőnek a 2. diára
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Mentse a PowerPoint prezentáció fájlt
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Ez a példa megmutatja, hogyan érhet el egy meglévő megjegyzést egy dián egy PowerPoint prezentációban.

```csharp
[C#]
// Példányosítja a Presentation osztályt
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Végigiterálja a CommentAuthors elemeket
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Végigiterálja a Comments elemeket
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Ez a példa megmutatja, hogyan adhat hozzá megjegyzéseket és hogyan kaphat válaszokat rájuk.

```csharp
[C#]
// Példányosítja a Presentation osztályt
using (Presentation pres = new Presentation())
{
    // Hozzáad egy megjegyzést
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Hozzáad egy választ a comment1-hez
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Hozzáad egy másik választ a comment1-hez
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Hozzáad egy választ a meglévő válaszhoz
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Kiírja a megjegyzések hierarchiáját a konzolra
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
    // Eltávolítja a comment1-et és az összes hozzá tartozó választ
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IComment](../icomment)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->