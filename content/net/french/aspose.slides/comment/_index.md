---
title: Comment
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un commentaire sur une diapositive.
type: docs
weight: 2530
url: /fr/aspose.slides/comment/
---

## Classe Comment

Représente un commentaire sur une diapositive.

```csharp
public class Comment : IComment
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Renvoie l'auteur d'un commentaire. En lecture seule [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Renvoie ou définit le moment de la création d'un commentaire. Si cette propriété est définie sur MinValue, cela signifie qu'aucun temps de commentaire n'est défini. En lecture/écriture DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Obtient ou définit le commentaire parent. En lecture/écriture [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Renvoie ou définit la position d'un commentaire sur une diapositive. En lecture/écriture PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Renvoie ou définit la diapositive parent d'un commentaire. En lecture seule [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Renvoie ou définit le texte brut d'un commentaire sur une diapositive. En lecture/écriture String. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Supprime le commentaire et toutes ses réponses de la collection parent. |

### Exemples

Cet exemple vous montre comment ajouter un commentaire à une diapositive dans une présentation PowerPoint.

```csharp
[C#]
// Instancie la classe Presentation
using (Presentation presentation = new Presentation())
{
    // Ajoute une diapositive vide
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Ajoute un auteur
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Définit la position pour les commentaires
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Ajoute un commentaire de diapositive pour un auteur sur la diapositive 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Ajoute un commentaire de diapositive pour un auteur sur la diapositive 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Enregistre le fichier de présentation PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Cet exemple vous montre comment accéder à un commentaire existant sur une diapositive dans une présentation PowerPoint.

```csharp
[C#]
// Instancie la classe Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Itère sur CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Itère sur Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Cet exemple vous montre comment ajouter des commentaires et obtenir des réponses à ceux-ci.

```csharp
[C#]
// Instancie la classe Presentation
using (Presentation pres = new Presentation())
{
    // Ajoute un commentaire
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Ajoute une réponse au commentaire1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Ajoute une autre réponse au commentaire1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Ajoute une réponse à une réponse existante
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Affiche la hiérarchie des commentaires sur la console
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
    // Supprime le commentaire1 et toutes ses réponses
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Voir Aussi

* interface [IComment](../icomment)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->