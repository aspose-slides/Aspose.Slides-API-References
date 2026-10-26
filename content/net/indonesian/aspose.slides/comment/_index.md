---
title: Comment
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili komentar pada slide.
type: docs
weight: 2620
url: /id/aspose.slides/comment/
---
## Kelas Comment

Mewakili komentar pada slide.

```csharp
public class Comment : IComment
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Mengembalikan penulis komentar. Hanya-baca [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Mengembalikan atau mengatur waktu pembuatan komentar. Menetapkan properti ini ke MinValue berarti tidak ada waktu komentar yang diatur. Baca/tulis DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Mengambil atau mengatur komentar induk. Baca/tulis [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Mengembalikan atau mengatur posisi komentar pada slide. Baca/tulis PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Mengembalikan atau mengatur slide induk dari komentar. Hanya-baca [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Mengembalikan atau mengatur teks polos komentar slide. Baca/tulis String. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Menghapus komentar dan semua balasannya dari koleksi induk. |

### Contoh

Contoh ini menunjukkan cara menambahkan komentar ke slide dalam presentasi PowerPoint.

```csharp
[C#]
// Membuat instance kelas Presentation
using (Presentation presentation = new Presentation())
{
    // Menambahkan slide kosong
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Menambahkan penulis
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Mengatur posisi komentar
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Menambahkan komentar slide untuk penulis pada slide 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Menambahkan komentar slide untuk penulis pada slide 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Menyimpan file Presentasi PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Contoh ini menunjukkan cara mengakses komentar yang ada pada slide dalam presentasi PowerPoint.

```csharp
[C#]
// Membuat instance kelas Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Iterasi CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Iterasi Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Contoh ini menunjukkan cara menambahkan komentar dan mendapatkan balasannya.

```csharp
[C#]
// Membuat instance kelas Presentation
using (Presentation pres = new Presentation())
{
    // Menambahkan komentar
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Menambahkan balasan ke comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Menambahkan balasan lain ke comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Menambahkan balasan ke balasan yang ada
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Menampilkan hierarki komentar di konsol
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
    // Menghapus comment1 dan semua balasannya
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* antarmuka [IComment](../icomment)
* ruang nama [Aspose.Slides](../../aspose.slides)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->