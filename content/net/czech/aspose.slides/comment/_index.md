---
title: Comment
second_title: Aspose.Sildes pro .NET API Reference
description: Representuje komentář na snímku.
type: docs
weight: 2600
url: /cs/aspose.slides/comment/
---
## Comment třída

Reprezentuje komentář na snímku.

```csharp
public class Comment : IComment
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Vrací autora komentáře. Pouze ke čtení [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Vrací nebo nastavuje čas vytvoření komentáře. Nastavení této vlastnosti na MinValue znamená, že čas komentáře není nastaven. Čtení/zápis DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Vrací nebo nastavuje nadřazený komentář. Čtení/zápis [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Vrací nebo nastavuje pozici komentáře na snímku. Čtení/zápis PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Vrací nebo nastavuje nadřazený snímek komentáře. Pouze ke čtení [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Vrací nebo nastavuje prostý text komentáře na snímku. Čtení/zápis String. |

## Metody

| Název | Popis |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Odstraní komentář a všechny jeho odpovědi z nadřazené kolekce. |

### Příklady

Tento příklad ukazuje, jak přidat komentář na snímek v prezentaci PowerPoint.

```csharp
[C#]
// Vytvoří instanci třídy Presentation
using (Presentation presentation = new Presentation())
{
    // Přidá prázdný snímek
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Přidá autora
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Nastaví pozici pro komentáře
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Přidá komentář ke snímku od autora na snímku 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Přidá komentář ke snímku od autora na snímku 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Uloží soubor prezentace PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Tento příklad ukazuje, jak získat přístup k existujícímu komentáři na snímku v prezentaci PowerPoint.

```csharp
[C#]
// Vytvoří instanci třídy Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Procházejte CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Procházejte komentáře
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Tento příklad ukazuje, jak přidávat komentáře a získávat na ně odpovědi.

```csharp
[C#]
// Vytvoří instanci třídy Presentation
using (Presentation pres = new Presentation())
{
    // Přidá komentář
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Přidá odpověď ke comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Přidá další odpověď ke comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Přidá odpověď k existující odpovědi
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Zobrazí hierarchii komentářů v konzole
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
    // Odstraní comment1 a všechny jeho odpovědi
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IComment](../icomment)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->