---
title: Comment
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un commento su una diapositiva.
type: docs
weight: 2620
url: /it/aspose.slides/comment/
---
## Comment classe

Rappresenta un commento su una diapositiva.

```csharp
public class Comment : IComment
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Restituisce l'autore di un commento. Sola lettura [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Restituisce o imposta l'ora di creazione di un commento. Impostare questa proprietà a MinValue indica che non è impostata alcuna ora del commento. Lettura/scrittura DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Ottiene o imposta il commento genitore. Lettura/scrittura [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Restituisce o imposta la posizione di un commento su una diapositiva. Lettura/scrittura PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Restituisce o imposta la diapositiva genitore di un commento. Sola lettura [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Restituisce o imposta il testo semplice di un commento su una diapositiva. Lettura/scrittura String. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Rimuove il commento e tutte le sue risposte dalla collezione genitore. |

### Esempi

Questo esempio mostra come aggiungere un commento a una diapositiva in una presentazione PowerPoint.

```csharp
[C#]
// Istanzia la classe Presentation
using (Presentation presentation = new Presentation())
{
    // Aggiunge una diapositiva vuota
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Aggiunge un autore
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Imposta la posizione per i commenti
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Aggiunge un commento alla diapositiva per un autore nella diapositiva 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Aggiunge un commento alla diapositiva per un autore nella diapositiva 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Salva il file PowerPoint Presentation
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Questo esempio mostra come accedere a un commento esistente su una diapositiva in una presentazione PowerPoint.

```csharp
[C#]
// Istanzia la classe Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Itera CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Itera Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Questo esempio mostra come aggiungere commenti e ottenere le risposte a essi.

```csharp
[C#]
// Istanzia la classe Presentation
using (Presentation pres = new Presentation())
{
    // Aggiunge un commento
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Aggiunge una risposta a comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Aggiunge un'altra risposta a comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Aggiunge una risposta a una risposta esistente
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Mostra la gerarchia dei commenti sulla console
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
    // Rimuove comment1 e tutte le risposte ad esso
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [IComment](../icomment)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->