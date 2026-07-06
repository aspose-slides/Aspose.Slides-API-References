---
title: Comment
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Đại diện cho một bình luận trên một slide.
type: docs
weight: 2620
url: /vi/aspose.slides/comment/
---
## Lớp Comment

Đại diện cho một bình luận trên một slide.

```csharp
public class Comment : IComment
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | Trả về tác giả của một bình luận. Chỉ đọc [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | Trả về hoặc đặt thời gian tạo bình luận. Đặt thuộc tính này thành MinValue có nghĩa là không có thời gian bình luận được đặt. Đọc/ghi DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | Lấy hoặc đặt bình luận cha. Đọc/ghi [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | Trả về hoặc đặt vị trí của bình luận trên slide. Đọc/ghi PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | Trả về hoặc đặt slide cha của một bình luận. Chỉ đọc [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | Trả về hoặc đặt văn bản thuần của một bình luận trên slide. Đọc/ghi String. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | Xóa bình luận và tất cả các phản hồi của nó khỏi bộ sưu tập cha. |

### Ví dụ

Ví dụ này cho thấy cách thêm một bình luận vào slide trong bản trình chiếu PowerPoint.

```csharp
[C#]
// Khởi tạo lớp Presentation
using (Presentation presentation = new Presentation())
{
    // Thêm một slide trống
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // Thêm một tác giả
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // Đặt vị trí cho các bình luận
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // Thêm bình luận slide cho tác giả trên slide 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // Thêm bình luận slide cho tác giả trên slide 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// Lưu tệp PowerPoint Presentation
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

Ví dụ này cho thấy cách truy cập một bình luận đã tồn tại trên slide trong bản trình chiếu PowerPoint.

```csharp
[C#]
// Khởi tạo lớp Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// Duyệt CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// Duyệt Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

Ví dụ này cho thấy cách thêm bình luận và lấy các phản hồi cho chúng.

```csharp
[C#]
// Khởi tạo lớp Presentation
using (Presentation pres = new Presentation())
{
    // Thêm một bình luận
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // Thêm một trả lời cho comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // Thêm một trả lời khác cho comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // Thêm một trả lời cho trả lời hiện có
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // Hiển thị cấu trúc phân cấp bình luận trên console
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
    // Xóa comment1 và tất cả các trả lời của nó
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IComment](../icomment)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->