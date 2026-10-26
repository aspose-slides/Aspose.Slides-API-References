---
title: Comment
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: نمایانگر یک نظر روی اسلاید.
type: docs
url: /fa/com.aspose.slides/comment/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

یک نظر روی اسلاید را نمایان می‌کند.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // یک نمونه از کلاس Presentation ایجاد می‌کند
>  Presentation presentation = new Presentation();
>  try {
>     // یک اسلاید خالی اضافه می‌کند
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // یک نویسنده اضافه می‌کند
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // موقعیت نظرات را تنظیم می‌کند
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // یک نظر اسلاید برای نویسنده در اسلاید 1 اضافه می‌کند
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // یک نظر اسلاید برای نویسنده در اسلاید 2 اضافه می‌کند
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// فایل ارائه PowerPoint را ذخیره می‌کند
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // یک نمونه از کلاس Presentation ایجاد می‌کند
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // تکرار CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // تکرار Comments
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
>  // یک نمونه از کلاس Presentation ایجاد می‌کند
>  Presentation pres = new Presentation();
>  try {
>     // یک نظر اضافه می‌کند
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // یک پاسخ به comment1 اضافه می‌کند
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // یک پاسخ دیگر به comment1 اضافه می‌کند
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // یک پاسخ به پاسخ موجود اضافه می‌کند
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // سلسله مراتب نظرات را در کنسول نمایش می‌دهد
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
>      // comment1 و تمام پاسخ‌های آن را حذف می‌کند
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getText()](#getText--) | متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [getCreatedTime()](#getCreatedTime--) | زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. |
| [getSlide()](#getSlide--) | اسلاید والد یک نظر را برمی‌گرداند یا تنظیم می‌کند. |
| [getAuthor()](#getAuthor--) | نویسنده یک نظر را برمی‌گرداند. |
| [getPosition()](#getPosition--) | موقعیت یک نظر روی اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | موقعیت یک نظر روی اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | نظر و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند. |
| [getParentComment()](#getParentComment--) | نظر والد را می‌گیرد یا تنظیم می‌کند. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | نظر والد را می‌گیرد یا تنظیم می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

متن ساده یک نظر اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به java.util.Date(Long.MIN_VALUE) به این معنی است که زمان نظری تنظیم نشده است. خواندنی/نوشتنی java.util.Date.

--------------------

زمان نظر یک پارامتر اختیاری است.

**بازگشت:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

زمان ایجاد یک نظر را برمی‌گرداند یا تنظیم می‌کند. تنظیم این ویژگی به java.util.Date(Long.MIN_VALUE) به این معنی است که زمان نظری تنظیم نشده است. خواندنی/نوشتنی java.util.Date.

--------------------

زمان نظر یک پارامتر اختیاری است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

اسلاید والد یک نظر را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی [ISlide](../../com.aspose.slides/islide).

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

نویسنده یک نظر را برمی‌گرداند. فقط-خواندنی [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**بازگشت:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

موقعیت یک نظر روی اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی android.graphics.PointF.

**بازگشت:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

موقعیت یک نظر روی اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی android.graphics.PointF.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

نظر و تمام پاسخ‌های آن را از مجموعه والد حذف می‌کند.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

نظر والد را می‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی [IComment](../../com.aspose.slides/icomment).

**بازگشت:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

نظر والد را می‌گیرد یا تنظیم می‌کند. خواندنی/نوشتنی [IComment](../../com.aspose.slides/icomment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject