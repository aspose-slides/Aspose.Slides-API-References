---
title: Comment
second_title: Aspose.Slides for Android via Java API 參考
description: 表示投影片上的註解。
type: docs
url: /zh-hant/com.aspose.slides/comment/
---
**繼承:**
java.lang.Object

**所有實作的介面:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

表示投影片上的註解。

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // 實例化 Presentation 類
>  Presentation presentation = new Presentation();
>  try {
>     // 新增空白投影片
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // 新增作者
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // 設定註解的位置
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // 為作者在投影片 1 上新增投影片註解
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // 為作者在投影片 2 上新增投影片註解
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// 儲存 PowerPoint 簡報檔案
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // 實例化 Presentation 類
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // 遍歷 CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // 遍歷 Comments
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
>  // 實例化 Presentation 類
>  Presentation pres = new Presentation();
>  try {
>     // 新增註解
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // 為 comment1 新增回覆
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // 為 comment1 再新增一個回覆
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // 為現有回覆新增回覆
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // 在主控台顯示註解層級結構
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
>      // 移除 comment1 及其所有回覆
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 傳回或設定投影片註解的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 傳回或設定投影片註解的純文字。 |
| [getCreatedTime()](#getCreatedTime--) | 傳回或設定註解建立的時間。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 傳回或設定註解建立的時間。 |
| [getSlide()](#getSlide--) | 傳回或設定註解的父投影片。 |
| [getAuthor()](#getAuthor--) | 傳回註解的作者。 |
| [getPosition()](#getPosition--) | 傳回或設定註解在投影片上的位置。 |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | 傳回或設定註解在投影片上的位置。 |
| [remove()](#remove--) | 從父集合中移除註解及其所有回覆。 |
| [getParentComment()](#getParentComment--) | 取得或設定父註解。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 取得或設定父註解。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

傳回或設定投影片註解的純文字。讀寫 String。

**傳回:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

傳回或設定投影片註解的純文字。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

傳回或設定註解建立的時間。將此屬性設定為 java.util.Date(Long.MIN_VALUE) 表示未設定註解時間。讀寫 java.util.Date。

**傳回:**
java.util.Date

--------------------

註解時間是可選的參數。

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

傳回或設定註解建立的時間。將此屬性設定為 java.util.Date(Long.MIN_VALUE) 表示未設定註解時間。讀寫 java.util.Date。

--------------------

註解時間是可選的參數。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

傳回或設定註解的父投影片。唯讀 [ISlide](../../com.aspose.slides/islide)。

**傳回:**
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

傳回註解的作者。唯讀 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**傳回:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

傳回或設定註解在投影片上的位置。讀寫 android.graphics.PointF。

**傳回:**
android.graphics.PointF

### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

傳回或設定註解在投影片上的位置。讀寫 android.graphics.PointF。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

從父集合中移除註解及其所有回覆。

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

取得或設定父註解。讀寫 [IComment](../../com.aspose.slides/icomment)。

**傳回:**
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

取得或設定父註解。讀寫 [IComment](../../com.aspose.slides/icomment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject