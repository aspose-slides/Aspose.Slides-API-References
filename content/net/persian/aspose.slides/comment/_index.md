---
title: Comment
second_title: Aspose.Sildes برای مرجع API .NET
description: یک نظر را روی اسلاید نشان می‌دهد.
type: docs
weight: 2620
url: /fa/aspose.slides/comment/
---
## Comment کلاس

Represents a comment on a slide.

```csharp
public class Comment : IComment
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | نویسنده‌ی یک کامنت را برمی‌گرداند. فقط خواندنی [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | زمان ایجاد یک کامنت را برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به MinValue به این معنی است که زمان کامنت تنظیم نشده است. قابل خواندن/نوشتن DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | کامنت والد را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | موقعیت یک کامنت روی اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | اسلاید والد یک کامنت را برمی‌گرداند یا تنظیم می‌کند. فقط خواندنی [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | متن ساده یک کامنت اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |

## متدها

| نام | توضیحات |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | کامنت و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند. |

### مثال‌ها

این مثال نشان می‌دهد چگونه یک کامنت به اسلایدی در ارائهٔ PowerPoint اضافه کنید.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد می‌کند
using (Presentation presentation = new Presentation())
{
    // یک اسلاید خالی اضافه می‌کند
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // یک نویسنده اضافه می‌کند
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // موقعیت نظرات را تنظیم می‌کند
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // یک نظر اسلاید برای یک نویسنده در اسلاید 1 اضافه می‌کند
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // یک نظر اسلاید برای یک نویسنده در اسلاید 2 اضافه می‌کند
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// فایل ارائه PowerPoint را ذخیره می‌کند
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

این مثال نشان می‌دهد چگونه به یک کامنت موجود روی اسلایدی در ارائهٔ PowerPoint دسترسی پیدا کنید.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد می‌کند
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// مرور CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// مرور Comments
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

این مثال نشان می‌دهد چگونه کامنت‌ها را اضافه کنید و پاسخ‌های آن‌ها را دریافت کنید.

```csharp
[C#]
// یک نمونه از کلاس Presentation ایجاد می‌کند
using (Presentation pres = new Presentation())
{
    // یک کامنت اضافه می‌کند
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // یک پاسخ به comment1 اضافه می‌کند
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // یک پاسخ دیگر به comment1 اضافه می‌کند
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // یک پاسخ به پاسخ موجود اضافه می‌کند
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // ساختار سلسله‌مراتب نظرات را در کنسول نمایش می‌دهد
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
    // comment1 و تمام پاسخ‌های آن را حذف می‌کند
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IComment](../icomment)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->