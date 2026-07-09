---
title: Comment
second_title: Aspose.Sildes voor .NET API Referentie
description: Stelt een opmerking op een dia voor.
type: docs
weight: 2620
url: /nl/aspose.slides/comment/
---
## Comment klasse

Stelt een opmerking op een dia voor.

```csharp
public class Comment : IComment
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Geeft de auteur van een opmerking terug. Alleen-lezen [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Geeft de tijd van een opmerkingcreatie terug of stelt deze in. Het instellen van deze eigenschap op MinValue betekent dat er geen opmerkingstijd is ingesteld. Lezen/Schrijven DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Haalt de bovenliggende opmerking op of stelt deze in. Lezen/Schrijven [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Geeft de positie van een opmerking op een dia terug of stelt deze in. Lezen/Schrijven PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Geeft de bovenliggende dia van een opmerking terug. Alleen-lezen [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Geeft de platte tekst van een dia-opmerking terug of stelt deze in. Lezen/Schrijven String. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Verwijdert de opmerking en al zijn antwoorden uit de bovenliggende collectie. |

### Voorbeelden

Dit voorbeeld laat zien hoe u een opmerking aan een dia in een PowerPoint-presentatie kunt toevoegen.

```csharp
[C#]
// Instantieert de Presentation klasse
using (Presentation presentation = new Presentation())
{
    // Voegt een lege dia toe
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Voegt een auteur toe
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Stelt de positie voor opmerkingen in
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Voegt een dia-opmerking toe voor een auteur op dia 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Voegt een dia-opmerking toe voor een auteur op dia 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Sla het PowerPoint-presentatiebestand op
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Dit voorbeeld laat zien hoe u een bestaande opmerking op een dia in een PowerPoint-presentatie kunt benaderen.

```csharp
[C#]
// Instantieert de Presentation klasse
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Itereren over CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Itereren over Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Dit voorbeeld laat zien hoe u opmerkingen kunt toevoegen en antwoorden kunt ophalen.

```csharp
[C#]
// Instantieert de Presentation klasse
using (Presentation pres = new Presentation())
{
    // Voegt een opmerking toe
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Voegt een antwoord toe aan comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Voegt nog een antwoord toe aan comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Voegt een antwoord toe aan een bestaand antwoord
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Toont de hiërarchie van opmerkingen in de console
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
    // Verwijdert comment1 en alle antwoorden erop
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IComment](../icomment)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->