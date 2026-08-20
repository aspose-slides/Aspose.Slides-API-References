---
title: Comment
second_title: Aspose.Slides 的 Java API 參考
description: 表示投影片上的註解。
type: docs
url: /zh-hant/com.aspose.slides/comment/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject  
```
public class Comment implements IComment, IDOMObject
```

表示投影片上的註解。

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // 實例化 Presentation 類別
>  Presentation presentation = new Presentation();
>  try {
>     // 新增空白投影片
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // 新增作者
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // 設定註解的位置
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // 為投影片 1 的作者新增投影片註解
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // 為投影片 2 的作者新增投影片註解
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// 儲存 PowerPoint 簡報檔案
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // 實例化 Presentation 類別
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // 迭代 CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // 迭代 Comments
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
>  // 實例化 Presentation 類別
>  Presentation pres = new Presentation();
>  try {
>     // 新增註解
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // 為 comment1 新增回覆
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // 為 comment1 新增另一筆回覆
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // 為已存在的回覆新增子回覆
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // 在控制台顯示註解階層結構
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
>      // 移除 comment1 以及其所有回覆
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 返回或設定投影片註解的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 返回或設定投影片註解的純文字。 |
| [getCreatedTime()](#getCreatedTime--) | 返回或設定註解建立的時間。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 返回或設定註解建立的時間。 |
| [getSlide()](#getSlide--) | 返回或設定註解的父投影片。 |
| [getAuthor()](#getAuthor--) | 返回註解的作者。 |
| [getPosition()](#getPosition--) | 返回或設定註解在投影片上的位置。 |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | 返回或設定註解在投影片上的位置。 |
| [remove()](#remove--) | 從父集合中移除註解及其所有回覆。 |
| [getParentComment()](#getParentComment--) | 取得或設定父註解。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 取得或設定父註解。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

返回或設定投影片註解的純文字。讀寫 String.

**返回值：**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

返回或設定投影片註解的純文字。讀寫 String.

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

返回或設定註解建立的時間。將此屬性設為 java.util.Date(Long.MIN_VALUE) 表示未設定註解時間。讀寫 java.util.Date.

--------------------

註解時間是可選參數。

**返回值：**  
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

返回或設定註解建立的時間。將此屬性設為 java.util.Date(Long.MIN_VALUE) 表示未設定註解時間。讀寫 java.util.Date.

--------------------

註解時間是可選參數。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

返回或設定註解的父投影片。唯讀 [ISlide](../../com.aspose.slides/islide).

**返回值：**  
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

返回註解的作者。唯讀 [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**返回值：**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

返回或設定註解在投影片上的位置。讀寫 java.awt.geom.Point2D.Float.

**返回值：**  
java.awt.geom.Point2D.Float

### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

返回或設定註解在投影片上的位置。讀寫 java.awt.geom.Point2D.Float.

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

從父集合中移除註解及其所有回覆。

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

取得或設定父註解。讀寫 [IComment](../../com.aspose.slides/icomment).

**返回值：**  
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

取得或設定父註解。讀寫 [IComment](../../com.aspose.slides/icomment).

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject.

**返回值：**  
com.aspose.slides.IDOMObject