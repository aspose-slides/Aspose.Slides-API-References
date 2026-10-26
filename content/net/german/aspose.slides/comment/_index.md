---
title: Comment
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt einen Kommentar auf einer Folie dar.
type: docs
weight: 2620
url: /de/aspose.slides/comment/
---
## Kommentar-Klasse

Stellt einen Kommentar auf einer Folie dar.

```csharp
public class Comment : IComment
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Gibt den Autor eines Kommentars zurück. Schreibgeschützt [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Gibt die Zeit der Erstellung eines Kommentars zurück oder legt sie fest. Das Setzen dieser Eigenschaft auf MinValue bedeutet, dass keine Kommentarzeit festgelegt ist. Lese/Schreib DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Gibt den übergeordneten Kommentar zurück oder legt ihn fest. Lese/Schreib [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. Lese/Schreib PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Gibt die übergeordnete Folie eines Kommentars zurück oder legt sie fest. Schreibgeschützt [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. Lese/Schreib String. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung. |

### Beispiele

Dieses Beispiel zeigt, wie Sie einen Kommentar zu einer Folie in einer PowerPoint-Präsentation hinzufügen.

```csharp
[C#]
// Instanziiert die Presentation-Klasse
using (Presentation presentation = new Presentation())
{
    // Fügt eine leere Folie hinzu
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Fügt einen Autor hinzu
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Setzt die Position für Kommentare
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Fügt einen Folienkommentar für einen Autor auf Folie 1 hinzu
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Fügt einen Folienkommentar für einen Autor auf Folie 2 hinzu
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Speichert die PowerPoint-Präsentationsdatei
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Dieses Beispiel zeigt, wie Sie auf einen vorhandenen Kommentar einer Folie in einer PowerPoint-Präsentation zugreifen.

```csharp
[C#]
// Instanziiert die Presentation-Klasse
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Durchläuft CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Durchläuft Kommentare
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Dieses Beispiel zeigt, wie Sie Kommentare hinzufügen und Antworten darauf erhalten.

```csharp
[C#]
// Instanziiert die Presentation-Klasse
using (Presentation pres = new Presentation())
{
    // Fügt einen Kommentar hinzu
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Fügt eine Antwort zu comment1 hinzu
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Fügt eine weitere Antwort zu comment1 hinzu
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Fügt eine Antwort auf eine vorhandene Antwort hinzu
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Gibt die Kommentarhierarchie auf der Konsole aus
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
    // Entfernt comment1 und alle zugehörigen Antworten
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Schnittstelle [IComment](../icomment)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->