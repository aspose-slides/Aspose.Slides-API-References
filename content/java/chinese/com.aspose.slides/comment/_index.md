---
title: Comment
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片上的注释。
type: docs
url: /zh/com.aspose.slides/comment/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

表示幻灯片上的注释。

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
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // 为作者在第 1 张幻灯片上添加幻灯片评论
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // 为作者在第 2 张幻灯片上添加幻灯片评论
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
>          // 遍历评论
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
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // 为 comment1 添加回复
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // 为 comment1 添加另一个回复
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // 为现有回复添加回复
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // 在控制台显示评论层级
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

## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 返回或设置幻灯片注释的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 返回或设置幻灯片注释的纯文本。 |
| [getCreatedTime()](#getCreatedTime--) | 返回或设置注释创建的时间。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 返回或设置注释创建的时间。 |
| [getSlide()](#getSlide--) | 返回或设置注释所属的父幻灯片。 |
| [getAuthor()](#getAuthor--) | 返回注释的作者。 |
| [getPosition()](#getPosition--) | 返回或设置注释在幻灯片上的位置。 |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | 返回或设置注释在幻灯片上的位置。 |
| [remove()](#remove--) | 从父集合中删除注释及其所有回复。 |
| [getParentComment()](#getParentComment--) | 获取或设置父注释。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 获取或设置父注释。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


返回或设置幻灯片注释的纯文本。 读/写 String。

**返回：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


返回或设置幻灯片注释的纯文本。 读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


返回或设置注释创建的时间。 将此属性设置为 java.util.Date(Long.MIN\_VALUE) 表示未设置注释时间。 读/写 java.util.Date。

--------------------

注释时间是可选参数。

**返回：**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


返回或设置注释创建的时间。 将此属性设置为 java.util.Date(Long.MIN\_VALUE) 表示未设置注释时间。 读/写 java.util.Date。

--------------------

注释时间是可选参数。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```


返回或设置注释所属的父幻灯片。 只读 [ISlide](../../com.aspose.slides/islide)。

**返回：**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


返回注释的作者。 只读 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**返回：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```


返回或设置注释在幻灯片上的位置。 读/写 java.awt.geom.Point2D.Float。

**返回：**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```


返回或设置注释在幻灯片上的位置。 读/写 java.awt.geom.Point2D.Float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```


从父集合中删除注释及其所有回复。

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


获取或设置父注释。 读/写 [IComment](../../com.aspose.slides/icomment)。

**返回：**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


获取或设置父注释。 读/写 [IComment](../../com.aspose.slides/icomment)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


返回 Parent\_Immediate 对象。 只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject