---
title: Comment
second_title: Aspose.Slides für .NET API Referenz
description: Stellt einen Kommentar zu einer Folie dar.
type: docs
weight: 2530
url: /de/aspose.slides/comment/
---

## Kommentar-Klasse

Stellt einen Kommentar zu einer Folie dar.

```csharp
public class Comment : IComment
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Gibt den Autor eines Kommentars zurück. Nur-lesend [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Gibt die Zeit der Kommentarschaffung zurück oder setzt sie. Das Setzen dieser Eigenschaft auf MinValue bedeutet, dass keine Kommentarzeit festgelegt ist. Lese-/Schreibbar DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Holt oder setzt den übergeordneten Kommentar. Lese-/Schreibbar [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Gibt die Position eines Kommentars auf einer Folie zurück oder setzt sie. Lese-/Schreibbar PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Gibt die übergeordnete Folie eines Kommentars zurück oder setzt sie. Nur-lesend [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Gibt den Klartext eines Folienkommentars zurück oder setzt ihn. Lese-/Schreibbar String. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung. |

### Beispiele

Dieses Beispiel zeigt, wie Sie einen Kommentar zu einer Folie in einer PowerPoint-Präsentation hinzufügen.

```csharp
[C#]
// Instanziiert die Präsentation-Klasse
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
    // Fügt Folienkommentar für einen Autor auf Folie 1 hinzu
    author.Comments.AddComment("Hallo Jawad, dies ist ein Folienkommentar", presentation.Slides[0], point, DateTime.Now);
    // Fügt Folienkommentar für einen Autor auf Folie 2 hinzu
    author.Comments.AddComment("Hallo Jawad, dies ist der zweite Folienkommentar", presentation.Slides[1], point, DateTime.Now);
    // Speichert die PowerPoint-Präsentationsdatei
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Dieses Beispiel zeigt, wie Sie auf einen vorhandenen Kommentar auf einer Folie in einer PowerPoint-Präsentation zugreifen.

```csharp
[C#]
// Instanziiert die Präsentation-Klasse
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
    // Iteriert über Kommentarautoren
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
        // Iteriert über Kommentare
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " hat Kommentar: " + comment.Text + " von Autor: " + comment.Author.Name + " veröffentlicht um: " + comment.CreatedTime + "\n");
        }
    }
}
```

Dieses Beispiel zeigt, wie Sie Kommentare hinzufügen und Antworten auf diese erhalten.

```csharp
[C#]
// Instanziiert die Präsentation-Klasse
using (Presentation pres = new Presentation())
{
    // Fügt einen Kommentar hinzu
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("Kommentar1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Fügt eine Antwort auf Kommentar1 hinzu
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autor_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("Antwort 1 für Kommentar 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Fügt eine weitere Antwort auf Kommentar1 hinzu
    IComment reply2 = author2.Comments.AddComment("Antwort 2 für Kommentar 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Fügt eine Antwort auf eine vorhandene Antwort hinzu
    IComment subReply = author1.Comments.AddComment("Unterantwort 3 für Antwort 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("Kommentar 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("Kommentar 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("Antwort 4 für Kommentar 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Zeigt die Kommentarhierarchie in der Konsole an
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
    // Entfernt Kommentar1 und alle Antworten darauf
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* interface [IComment](../icomment)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->