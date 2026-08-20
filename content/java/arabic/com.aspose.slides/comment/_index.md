---
title: Comment
second_title: مرجع Aspose.Slides لـ Java API
description: يمثل تعليقا على شريحة.
type: docs
url: /ar/com.aspose.slides/comment/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject  
```
public class Comment implements IComment, IDOMObject
```

يمثل تعليقًا على شريحة.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // ينشئ فئة Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // يضيف شريحة فارغة
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // يضيف مؤلفًا
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // يضبط موضع التعليقات
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // يضيف تعليق شريحة لمؤلف على الشريحة 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // يضيف تعليق شريحة لمؤلف على الشريحة 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// يحفظ ملف عرض PowerPoint
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // ينشئ فئة Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // التنقل عبر CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // التنقل عبر التعليقات
>          for (IComment comment1 : author.getComments())
>          {
>              Comment comment = (Comment) comment1;
>              System.out.println("ISlide :" + comment.getSlide().getSlideNumber() + " has comment: " + comment.getText() + " with Author: " + comment.getAuthor().getName() + " posted on time :" + comment.getCreatedTime().toString() + "\n");
>          }
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to add comments and get replies to them.
>  
>  // ينشئ فئة Presentation
>  Presentation pres = new Presentation();
>  try {
>     // يضيف تعليقًا
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // يضيف ردًا على comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // يضيف ردًا آخر على comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // يضيف ردًا على رد موجود
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // يعرض تسلسل التعليقات على وحدة التحكم
>      ISlide slide = pres.getSlides().get_Item(0);
>      IComment[] comments = slide.getSlideComments(null);
>      for (int i = 0; i < comments.length; i++)
>      {
>          IComment comment = comments[i];
>          while (comment.getParentComment() != null)
>          {
>              System.out.println("\t");
>              comment = comment.getParentComment();
>          }
>          System.out.println(comments[i].getAuthor().getName() + " : " + comments[i].getText());
>      }
>      pres.save("parent_comment.pptx",SaveFormat.Pptx);
>      // يزيل comment1 وجميع الردود عليها
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | إرجاع أو تعيين النص العادي لتعليق شريحة. |
| [setText(String value)](#setText-java.lang.String-) | إرجاع أو تعيين النص العادي لتعليق شريحة. |
| [getCreatedTime()](#getCreatedTime--) | إرجاع أو تعيين وقت إنشاء التعليق. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | إرجاع أو تعيين وقت إنشاء التعليق. |
| [getSlide()](#getSlide--) | إرجاع أو تعيين الشريحة الأصلية للتعليق. |
| [getAuthor()](#getAuthor--) | إرجاع مؤلف التعليق. |
| [getPosition()](#getPosition--) | إرجاع أو تعيين موضع التعليق على الشريحة. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | إرجاع أو تعيين موضع التعليق على الشريحة. |
| [remove()](#remove--) | إزالة التعليق وكل ردوده من التجميع الأصلي. |
| [getParentComment()](#getParentComment--) | إرجاع أو تعيين التعليق الأب. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | إرجاع أو تعيين التعليق الأب. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

إرجاع أو تعيين النص العادي لتعليق شريحة. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

إرجاع أو تعيين النص العادي لتعليق شريحة. قراءة/كتابة String.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

إرجاع أو تعيين وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN\_VALUE) يعني عدم تعيين وقت التعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معامل اختياري.

**الإرجاع:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

إرجاع أو تعيين وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN\_VALUE) يعني عدم تعيين وقت التعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معامل اختياري.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

إرجاع أو تعيين الشريحة الأصلية للتعليق. قراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**  
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

إرجاع مؤلف التعليق. قراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**الإرجاع:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

إرجاع أو تعيين موضع التعليق على الشريحة. قراءة/كتابة java.awt.geom.Point2D.Float.

**الإرجاع:**  
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

إرجاع أو تعيين موضع التعليق على الشريحة. قراءة/كتابة java.awt.geom.Point2D.Float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public final void remove()
```

إزالة التعليق وكل ردوده من التجميع الأصلي.
### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

إرجاع أو تعيين التعليق الأب. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**الإرجاع:**  
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

إرجاع أو تعيين التعليق الأب. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject