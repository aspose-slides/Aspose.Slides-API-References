---
title: Comment
second_title: Aspose.Sildes للـ .NET مرجع API
description: يمثل تعليقا على شريحة.
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
| [Author](../../aspose.slides/comment/author) { get; } | يرجع مؤلف التعليق. للقراءة فقط [`ICommentAuthor`](../icommentauthor). |
| [CreatedTime](../../aspose.slides/comment/createdtime) { get; set; } | يرجع أو يضبط وقت إنشاء التعليق. ضبط هذه الخاصية إلى MinValue يعني عدم تعيين وقت التعليق. قراءة/كتابة DateTime. |
| [ParentComment](../../aspose.slides/comment/parentcomment) { get; set; } | يحصل أو يضبط التعليق الأصل. قراءة/كتابة [`IComment`](../icomment). |
| [Position](../../aspose.slides/comment/position) { get; set; } | يرجع أو يضبط موضع التعليق على شريحة. قراءة/كتابة PointF. |
| [Slide](../../aspose.slides/comment/slide) { get; } | يرجع أو يضبط الشريحة الأصل للتعليق. للقراءة فقط [`ISlide`](../islide). |
| [Text](../../aspose.slides/comment/text) { get; set; } | يرجع أو يضبط النص العادي لتعليق الشريحة. قراءة/كتابة String. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Remove](../../aspose.slides/comment/remove)() | يزيل التعليق وجميع الردود الخاصة به من المجموعة الأصلية. |

### أمثلة

يوضح هذا المثال كيفية إضافة تعليق إلى شريحة في عرض تقديمي PowerPoint.

```csharp
[C#]
// يقوم بإنشاء فئة Presentation
using (Presentation presentation = new Presentation())
{
    // يضيف شريحة فارغة
    presentation.Slides.AddEmptySlide(presentation.LayoutSlides[0]);
    // يضيف مؤلفًا
    ICommentAuthor author = presentation.CommentAuthors.AddAuthor("Jawad", "MF");
    // يحدد موقع التعليقات
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
// يقوم بإنشاء فئة Presentation
using (Presentation presentation = new Presentation("Comments1.pptx"))
{
	// التكرار على CommentAuthors
    foreach (var commentAuthor in presentation.CommentAuthors)
    {
        var author = (CommentAuthor) commentAuthor;
		// التكرار على Comments
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
// يقوم بإنشاء فئة Presentation
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
    // يضيف ردًا على الرد الموجود
    IComment subReply = author1.Comments.AddComment("subreply 3 for reply 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    subReply.ParentComment = reply2;
    IComment comment2 = author2.Comments.AddComment("comment 2", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment comment3 = author2.Comments.AddComment("comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    IComment reply3 = author1.Comments.AddComment("reply 4 for comment 3", pres.Slides[0], new PointF(10, 10), DateTime.Now);
    reply3.ParentComment = comment3;
    // يعرض هيكلية التعليقات على وحدة التحكم
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
* نطاق الاسم [Aspose.Slides](../../aspose.slides)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->