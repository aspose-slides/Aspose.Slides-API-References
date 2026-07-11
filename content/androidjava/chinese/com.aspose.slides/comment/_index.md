---
title: Comment
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的评论。
type: docs
url: /zh/com.aspose.slides/comment/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

表示幻灯片上的评论。

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // 实例化 Presentation 类
>  Presentation presentation = new Presentation();
>  try {
>     // 添加空幻灯片
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // 添加作者
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // 设置评论的位置
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // 为作者在第 1 张幻灯片添加评论
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // 为作者在第 2 张幻灯片添加评论
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// 保存 PowerPoint 演示文稿文件
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // 实例化 Presentation 类
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // 遍历 CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // 遍历 Comments
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
>  // 实例化 Presentation 类
>  Presentation pres = new Presentation();
>  try {
>     // 添加评论
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // 为 comment1 添加回复
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // 为 comment1 再添加一个回复
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // 为已有回复添加回复
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // 在控制台显示评论层级结构
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
>      // 删除 comment1 及其所有回复
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Returns or sets the plain text of a slide comment. |
| [setText(String value)](#setText-java.lang.String-) | Returns or sets the plain text of a slide comment. |
| [getCreatedTime()](#getCreatedTime--) | Returns or sets the time of a comment creation. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returns or sets the time of a comment creation. |
| [getSlide()](#getSlide--) | Returns or sets the parent slide of a comment. |
| [getAuthor()](#getAuthor--) | Returns the author of a comment. |
| [getPosition()](#getPosition--) | Returns or sets the position of a comment on a slide. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Returns or sets the position of a comment on a slide. |
| [remove()](#remove--) | Removes comment and all its replies from the parent collection. |
| [getParentComment()](#getParentComment--) | Gets or sets parent comment. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Gets or sets parent comment. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Returns or sets the plain text of a slide comment. Read/write String.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Returns or sets the plain text of a slide comment. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date.

--------------------

Comment time is an optional parameter.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

返回或设置评论创建的时间。将此属性设置为 java.util.Date(Long.MIN_VALUE) 表示未设置评论时间。读/写 java.util.Date.

--------------------

评论时间是可选参数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Returns or sets the parent slide of a comment. Read-only [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Returns the author of a comment. Read-only [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Returns or sets the position of a comment on a slide. Read/write android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Returns or sets the position of a comment on a slide. Read/write android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

Removes comment and all its replies from the parent collection.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Gets or sets parent comment. Read/write [IComment](../../com.aspose.slides/icomment).

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Gets or sets parent comment. Read/write [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject