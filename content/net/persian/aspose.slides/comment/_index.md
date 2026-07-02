---
title: Comment
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر یک نظر بر روی یک اسلاید است.
type: docs
weight: 2620
url: /fa/aspose.slides/comment/
---
## کلاس Comment

نمایش یک نظر بر روی یک اسلاید.

```csharp
public class Comment : IComment
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | نویسنده‌ی یک نظر را باز می‌گرداند. فقط-خواندنی [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | زمان ایجاد یک نظر را باز می‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به MinValue به معنای عدم تنظیم زمان نظر است. قابل خواندن/نوشتن DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | نظر والد را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | موقعیت یک نظر بر روی اسلاید را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | اسلاید والد یک نظر را باز می‌گرداند یا تنظیم می‌کند. فقط-خواندنی [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | متن ساده‌ی یک نظر اسلاید را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |

## متدها

| نام | توضیحات |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | نظر و همه پاسخ‌های آن را از مجموعه پدر حذف می‌کند. |

### مثال‌ها

این مثال نشان می‌دهد چگونه یک نظر به اسلایدی در یک ارائه PowerPoint اضافه کنید.

```csharp
[C#]
// یک شی از کلاس Presentation ایجاد می‌کند
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
    // یک نظر اسلاید برای نویسنده در اسلاید 1 اضافه می‌کند
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // یک نظر اسلاید برای نویسنده در اسلاید 2 اضافه می‌کند
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// فایل ارائه PowerPoint را ذخیره می‌کند
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

این مثال نشان می‌دهد چگونه به یک نظر موجود در اسلایدی از یک ارائه PowerPoint دسترسی پیدا کنید.

```csharp
[C#]
// یک شی از کلاس Presentation ایجاد می‌کند
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

این مثال نشان می‌دهد چگونه نظرات را اضافه کنید و پاسخ‌های آن‌ها را دریافت کنید.

```csharp
[C#]
// یک شی از کلاس Presentation ایجاد می‌کند
using (Presentation pres = new Presentation())
{
    // یک نظر اضافه می‌کند
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // پاسخی به comment1 اضافه می‌کند
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // پاسخ دیگری به comment1 اضافه می‌کند
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // پاسخی به پاسخ موجود اضافه می‌کند
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // سلسله‌مرجع نظرات را در کنسول نمایش می‌دهد
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
    // comment1 و همهٔ پاسخ‌های آن را حذف می‌کند
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* رابط [IComment](../icomment)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبل [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->