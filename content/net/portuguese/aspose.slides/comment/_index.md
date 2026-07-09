---
title: Comment
second_title: Aspose.Sildes para .NET Referência da API
description: Representa um comentário em um slide.
type: docs
weight: 2620
url: /pt/aspose.slides/comment/
---
## Comment classe

Representa um comentário em um slide.

```csharp
public class Comment : IComment
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Retorna o autor de um comentário. Somente leitura [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Retorna ou define o horário de criação de um comentário. Definir esta propriedade como MinValue significa que nenhum horário de comentário está definido. Leitura/gravação DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Obtém ou define o comentário pai. Leitura/gravação [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Retorna ou define a posição de um comentário em um slide. Leitura/gravação PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Retorna ou define o slide pai de um comentário. Somente leitura [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Retorna ou define o texto simples de um comentário em um slide. Leitura/gravação String. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Remove o comentário e todas as suas respostas da coleção pai. |

### Exemplos

Este exemplo mostra como adicionar um comentário a um slide em uma apresentação do PowerPoint.

```csharp
[C#]
// Instancia a classe Presentation
using (Presentation presentation = new Presentation())
{
    // Adiciona um slide vazio
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Adiciona um autor
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Define a posição para comentários
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Adiciona comentário de slide para um autor no slide 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Adiciona comentário de slide para um autor no slide 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Salva o arquivo de apresentação PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Este exemplo mostra como acessar um comentário existente em um slide em uma apresentação do PowerPoint.

```csharp
[C#]
// Instancia a classe Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Itera sobre CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Itera sobre Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Este exemplo mostra como adicionar comentários e obter respostas a eles.

```csharp
[C#]
// Instancia a classe Presentation
using (Presentation pres = new Presentation())
{
    // Adiciona um comentário
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Adiciona uma resposta ao comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Adiciona outra resposta ao comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Adiciona uma resposta a uma resposta existente
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Exibe a hierarquia de comentários no console
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
    // Remove o comment1 e todas as respostas a ele
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Ver também

* interface [IComment](../icomment)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->