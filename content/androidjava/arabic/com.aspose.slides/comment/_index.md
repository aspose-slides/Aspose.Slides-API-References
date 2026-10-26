---
title: Comment
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل تعليقا على شريحة.
type: docs
url: /ar/com.aspose.slides/comment/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفّذة:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

يمثّل تعليقا على الشريحة.

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
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // يضيف تعليق شريحة للمؤلف على الشريحة 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // يضيف تعليق شريحة للمؤلف على الشريحة 2
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
>      // التكرار عبر CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // التكرار عبر التعليقات
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
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // يضيف ردًا على comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // يضيف ردًا آخر على comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // يضيف ردًا على الرد الموجود
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // يعرض تسلسل التعليقات في وحدة التحكم
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
>      // يزيل comment1 وجميع الردود عليه
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | يعيد أو يضبط النص العادي لتعليق على الشريحة. |
| [setText(String value)](#setText-java.lang.String-) | يعيد أو يضبط النص العادي لتعليق على الشريحة. |
| [getCreatedTime()](#getCreatedTime--) | يعيد أو يضبط وقت إنشاء التعليق. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | يعيد أو يضبط وقت إنشاء التعليق. |
| [getSlide()](#getSlide--) | يعيد أو يضبط الشريحة الأصلية للتعليق. |
| [getAuthor()](#getAuthor--) | يعيد مؤلف التعليق. |
| [getPosition()](#getPosition--) | يعيد أو يضبط موضع التعليق على الشريحة. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | يعيد أو يضبط موضع التعليق على الشريحة. |
| [remove()](#remove--) | يزيل التعليق وجميع ردوده من المجموعة الأصلية. |
| [getParentComment()](#getParentComment--) | يحصل أو يضبط التعليق الأصلي. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | يحصل أو يضبط التعليق الأصلي. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

يعيد أو يضبط النص العادي لتعليق على الشريحة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

يعيد أو يضبط النص العادي لتعليق على الشريحة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

يعيد أو يضبط وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN\_VALUE) يعني عدم تعيين وقت للتعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معلمة اختيارية.

**الإرجاع:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

يعيد أو يضبط وقت إنشاء التعليق. تعيين هذه الخاصية إلى java.util.Date(Long.MIN\_VALUE) يعني عدم تعيين وقت للتعليق. قراءة/كتابة java.util.Date.

--------------------

وقت التعليق هو معلمة اختيارية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

يعيد أو يضبط الشريحة الأصلية للتعليق. قراءة فقط [ISlide](../../com.aspose.slides/islide).

**الإرجاع:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

يعيد مؤلف التعليق. قراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**الإرجاع:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

يعيد أو يضبط موضع التعليق على الشريحة. قراءة/كتابة android.graphics.PointF.

**الإرجاع:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

يعيد أو يضبط موضع التعليق على الشريحة. قراءة/كتابة android.graphics.PointF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public final void remove()
```

يزيل التعليق وجميع ردوده من المجموعة الأصلية.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

يحصل أو يضبط التعليق الأصلي. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**الإرجاع:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

يحصل أو يضبط التعليق الأصلي. قراءة/كتابة [IComment](../../com.aspose.slides/icomment).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject