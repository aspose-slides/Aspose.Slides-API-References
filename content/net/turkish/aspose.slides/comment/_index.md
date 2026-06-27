---
title: Comment
second_title: Aspose.Sildes for .NET API Referansı
description: Bir slayttaki yorumu temsil eder.
type: docs
weight: 2600
url: /tr/aspose.slides/comment/
---
## Comment sınıfı

Bir slayttaki yorumu temsil eder.

```csharp
public class Comment : IComment
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Bir yorumun yazarını döndürür. Salt-okunur [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Bir yorumun oluşturulma zamanını döndürür veya ayarlar. Bu özelliği MinValue olarak ayarlamak, yorum zamanının ayarlanmadığını gösterir. Okunur/yazılabilir DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Üst yorumu alır veya ayarlar. Okunur/yazılabilir [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Bir slayttaki yorumun konumunu döndürür veya ayarlar. Okunur/yazılabilir PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Bir yorumun üst slaytını döndürür. Salt-okunur [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Bir slayt yorumunun düz metnini döndürür veya ayarlar. Okunur/yazılabilir String. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Yorumu ve tüm yanıtlarını üst koleksiyondan kaldırır. |

### Örnekler

Bu örnek, bir PowerPoint sunumunda bir slayta yorum eklemenin nasıl yapılacağını gösterir.

```csharp
[C#]
// Presentation sınıfını örnekler
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
    // 1. slaytta yazar için slayt yorumu ekler
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // 2. slaytta yazar için slayt yorumu ekler
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// PowerPoint Sunum dosyasını kaydet
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Bu örnek, bir PowerPoint sunumunda bir slayttaki mevcut bir yoruma nasıl erişileceğini gösterir.

```csharp
[C#]
// Presentation sınıfını örnekler
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// CommentAuthors üzerinden döner
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Comments üzerinden döner
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Bu örnek, yorum eklemenin ve yanıtlarını almanın nasıl yapılacağını gösterir.

```csharp
[C#]
// Presentation sınıfını örnekler
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
    // Yorum hiyerarşisini konsolda gösterir
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
    // comment1'i ve ona bağlı tüm yanıtları kaldırır
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Ayrıca Bakınız

* arayüz [IComment](../icomment)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->