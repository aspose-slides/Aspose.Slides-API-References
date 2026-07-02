---
title: Comment
second_title: Aspose.Sildes voor .NET API-referentie
description: Representeert een opmerking op een dia.
type: docs
weight: 2620
url: /nl/aspose.slides/comment/
---
## Comment klasse

Representeert een opmerking op een dia.

```csharp
public class Comment : IComment
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Retourneert de auteur van een opmerking. Alleen-lezen [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Retourneert of stelt de tijd van een opmerking in. Het instellen van deze eigenschap op MinValue betekent dat er geen opmerkingstijd is ingesteld. Lezen/schrijven DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Haalt op of stelt de bovenliggende opmerking in. Lezen/schrijven [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Retourneert of stelt de positie van een opmerking op een dia in. Lezen/schrijven PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Retourneert de bovenliggende dia van een opmerking. Alleen-lezen [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Retourneert of stelt de platte tekst van een diaopmerking in. Lezen/schrijven String. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Verwijdert de opmerking en al zijn antwoorden uit de bovenliggende collectie. |

### Voorbeelden

Dit voorbeeld toont hoe u een opmerking aan een dia in een PowerPoint-presentatie kunt toevoegen.

```csharp
[C#]
// Maakt een instantie van de Presentation-klasse
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
    // Voegt een diaopmerking toe voor een auteur op dia 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Voegt een diaopmerking toe voor een auteur op dia 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Sla het PowerPoint-presentatiebestand op
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Dit voorbeeld toont hoe u toegang krijgt tot een bestaande opmerking op een dia in een PowerPoint-presentatie.

```csharp
[C#]
// Instantieert de Presentation-klasse
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Itereer over CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Itereer over Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Dit voorbeeld toont hoe u opmerkingen kunt toevoegen en antwoorden hierop kunt krijgen.

```csharp
[C#]
// Instantieert de Presentation-klasse
using (Presentation pres = new Presentation())
{
    // Voegt een opmerking toe
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Voegt een antwoord toe aan comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Voegt een ander antwoord toe aan comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Voegt een antwoord toe aan een bestaand antwoord
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Toont de hiërarchie van opmerkingen op de console
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
    // Verwijdert comment1 en alle antwoorden daarop
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IComment](../icomment)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->