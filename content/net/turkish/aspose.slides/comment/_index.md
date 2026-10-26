---
title: Comment
second_title: Aspose.Slides for .NET API Referansı
description: Bir slayttaki yorumu temsil eder.
type: docs
weight: 2620
url: /tr/aspose.slides/comment/
---
## Comment sınıfı

Bir slayt üzerindeki yorumu temsil eder.

```csharp
public class Comment : IComment
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Bir yorumun yazarını döndürür. Salt-okunur [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Bir yorumun oluşturulma zamanını döndürür veya ayarlar. Bu özelliği MinValue olarak ayarlamak, yorum zamanının ayarlanmadığı anlamına gelir. Okunabilir/yazılabilir DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Üst yorumu alır veya ayarlar. Okunabilir/yazılabilir [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Bir slayttaki yorumun konumunu döndürür veya ayarlar. Okunabilir/yazılabilir PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Bir yorumun üst slaydını döndürür veya ayarlar. Salt-okunur [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Bir slayt yorumunun düz metnini döndürür veya ayarlar. Okunabilir/yazılabilir String. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Yorumu ve tüm yanıtlarını üst koleksiyondan kaldırır. |

### Örnekler

Bu örnek, bir PowerPoint sunumunda bir slayta yorum eklemenin nasıl yapılacağını gösterir.

```csharp
[C#]
// Presentation sınıfının bir örneğini oluşturur
using (Presentation presentation = new Presentation())
{
    // Boş bir slayt ekler
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Bir yazar ekler
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Yorumların konumunu ayarlar
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Yazar için slayt 1'de slayt yorumu ekler
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Yazar için slayt 2'de slayt yorumu ekler
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// PowerPoint Sunum dosyasını kaydet
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Bu örnek, bir PowerPoint sunumunda bir slayttaki mevcut yoruma nasıl erişileceğini gösterir.

```csharp
[C#]
// Presentation sınıfının bir örneğini oluşturur
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// CommentAuthors koleksiyonunu dolaşır
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Yorumları dolaşır
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Bu örnek, yorum eklemeyi ve yanıtlarını almayı nasıl yapacağınızı gösterir.

```csharp
[C#]
// Presentation sınıfının bir örneğini oluşturur
using (Presentation pres = new Presentation())
{
    // Bir yorum ekler
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // comment1'e bir yanıt ekler
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // comment1'e başka bir yanıt ekler
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Mevcut yanıta bir yanıt ekler
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Yorum hiyerarşisini konsola gösterir
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
    // comment1 ve ona ait tüm yanıtları kaldırır
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Ayrıca

* arayüz [IComment](../icomment)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->