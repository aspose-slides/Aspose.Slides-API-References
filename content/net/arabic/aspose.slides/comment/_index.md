---
title: Comment
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل تعليقًا على شريحة.
type: docs
weight: 2620
url: /ar/aspose.slides/comment/
---
## فئة Comment

يمثل تعليقًا على شريحة.

```csharp
public class Comment : IComment
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Author](../../aspose.slides/comment/author) { get; } | يعيد مؤلف التعليق. قراءة فقط [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | يعيد أو يضبط وقت إنشاء التعليق. تعيين هذه الخاصية إلى MinValue يعني عدم تعيين وقت للتعليق. قراءة/كتابة DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | يحصل أو يضبط التعليق الأب. قراءة/كتابة [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | يعيد أو يضبط موضع التعليق على شريحة. قراءة/كتابة PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | يعيد أو يضبط الشريحة الأم للتعليق. قراءة فقط [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | يعيد أو يضبط النص العادي لتعليق الشريحة. قراءة/كتابة String. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | يزيل التعليق وجميع ردوده من المجموعة الأصلية. |

### أمثلة

يوضح هذا المثال كيفية إضافة تعليق إلى شريحة في عرض تقديمي PowerPoint.

```csharp
[C#]
// تهيئة فئة Presentation
using (Presentation presentation = new Presentation())
{
    // يضيف شريحة فارغة
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // يضيف مؤلفًا
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // يحدد موضع التعليقات
    PointF point = new PointF();
    point.X = 0.2f;
    point.Y = 0.2f;
    // يضيف تعليق شريحة لمؤلف على الشريحة 1
    author.Comments.AddComment("Hello Jawad, this is slide comment", presentation.Slides[0], point, DateTime.Now);
    // يضيف تعليق شريحة لمؤلف على الشريحة 2
    author.Comments.AddComment("Hello Jawad, this is second slide comment", presentation.Slides[1], point, DateTime.Now);
	// حفظ ملف عرض PowerPoint
    presentation.Save("Comments_out.pptx", SaveFormat.Pptx);
}
```

يوضح هذا المثال كيفية الوصول إلى تعليق موجود على شريحة في عرض تقديمي PowerPoint.

```csharp
[C#]
// إنشاء كائن من فئة Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// التنقل عبر CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// التنقل عبر التعليقات
        foreach (var comment1 in author.Comments)
        {
            var comment = (Comment) comment1;
            Console.WriteLine("ISlide :" + comment.Slide.SlideNumber + " has comment: " + comment.Text + " with Author: " + comment.Author.Name + " posted on time :" + comment.CreatedTime + "\n");
        }
    }
}
```

يوضح هذا المثال كيفية إضافة تعليقات والحصول على الردود عليها.

```csharp
[C#]
// إنشاء كائن من فئة Presentation
using (Presentation pres = new Presentation())
{
    // يضيف تعليقًا
    ICommentAuthor author1 = pres.CommentAuthors.AddAuthor("Author_1", "A.A.");
    IComment comment1 = author1.Comments.AddComment("comment1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    // يضيف ردًا على comment1
    ICommentAuthor author2 = pres.CommentAuthors.AddAuthor("Autror_2", "B.B.");
    IComment reply1 = author2.Comments.AddComment("reply 1 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply1.ParentComment = comment1;
    // يضيف ردًا آخر على comment1
    IComment reply2 = author2.Comments.AddComment("reply 2 for comment 1", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply2.ParentComment = comment1;
    // يضيف ردًا على رد موجود
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // يعرض تسلسل التعليقات في وحدة التحكم
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
    // يزيل comment1 وجميع الردود عليه
    comment1.Remove();
    pres.Save("remove_comment.pptx", SaveFormat.Pptx);
}
```

### انظر أيضًا

* واجهة [IComment](../icomment)
* مساحة الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->