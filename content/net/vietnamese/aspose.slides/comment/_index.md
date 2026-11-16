---
title: Comment
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một comment trên một slide.
type: docs
weight: 2640
url: /vi/aspose.slides/comment/
---
## Lớp Comment

Đại diện cho một comment trên một slide.

```csharp
public class Comment : IComment
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Trả về tác giả của một comment. Chỉ đọc [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Trả về hoặc đặt thời gian tạo một comment. Đặt thuộc tính này thành MinValue có nghĩa là không có thời gian comment nào được đặt. Đọc/ghi DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Lấy hoặc đặt comment cha. Đọc/ghi [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Trả về hoặc đặt vị trí của một comment trên một slide. Đọc/ghi PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Trả về slide cha của một comment. Chỉ đọc [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Trả về hoặc đặt văn bản thuần của một comment trên slide. Đọc/ghi String. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Xóa comment và tất cả các phản hồi của nó khỏi collection cha. |

### Ví dụ

Ví dụ này cho bạn thấy cách thêm một comment vào một slide trong bài thuyết trình PowerPoint.

```csharp
[C#]
// Khởi tạo lớp Presentation
using (Presentation presentation = new Presentation())
{
    // Thêm một slide trống
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Thêm một tác giả
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Đặt vị trí cho các comment
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Thêm comment slide cho một tác giả trên slide 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Thêm comment slide cho một tác giả trên slide 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Lưu tệp PowerPoint Presentation
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Ví dụ này cho bạn thấy cách truy cập một comment hiện có trên một slide trong bài thuyết trình PowerPoint.

```csharp
[C#]
// Khởi tạo lớp Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Duyệt qua CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Duyệt qua Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Ví dụ này cho bạn thấy cách thêm comment và lấy phản hồi cho chúng.

```csharp
[C#]
// Khởi tạo lớp Presentation
using (Presentation pres = new Presentation())
{
    // Thêm một comment
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Thêm một phản hồi cho comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Thêm một phản hồi khác cho comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Thêm một phản hồi cho phản hồi hiện có
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Hiển thị cấu trúc phân cấp các comment trên console
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
    // Xóa comment1 và tất cả các phản hồi của nó
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IComment](../icomment)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->