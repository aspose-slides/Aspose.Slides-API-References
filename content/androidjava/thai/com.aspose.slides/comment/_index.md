---
title: Comment
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงความคิดเห็นบนสไลด์
type: docs
url: /th/com.aspose.slides/comment/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

แสดงถึงความคิดเห็นบนสไลด์หนึ่ง.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // เพิ่มสไลด์เปล่า
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // เพิ่มผู้เขียน
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // ตั้งค่าตำแหน่งสำหรับความคิดเห็น
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // เพิ่มความคิดเห็นสไลด์สำหรับผู้เขียนบนสไลด์ที่ 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // เพิ่มความคิดเห็นสไลด์สำหรับผู้เขียนบนสไลด์ที่ 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// บันทึกไฟล์ PowerPoint Presentation
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // วนซ้ำ CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // วนซ้ำ Comments
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
>  // สร้างอินสแตนซ์ของคลาส Presentation
>  Presentation pres = new Presentation();
>  try {
>     // เพิ่มความคิดเห็น
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // เพิ่มการตอบกลับให้กับ comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // เพิ่มการตอบกลับอีกหนึ่งรายการให้กับ comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // เพิ่มการตอบกลับให้กับการตอบกลับที่มีอยู่
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // แสดงลำดับขั้นของความคิดเห็นบนคอนโซล
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
>      // ลบ comment1 และการตอบกลับทั้งหมดของมัน
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getText()](#getText--) | คืนค่า หรือกำหนดข้อความธรรมดาของความคิดเห็นบนสไลด์. |
| [setText(String value)](#setText-java.lang.String-) | คืนค่า หรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. |
| [getCreatedTime()](#getCreatedTime--) | คืนค่า หรือกำหนดเวลาการสร้างความคิดเห็น. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | คืนค่า หรือกำหนดเวลาการสร้างความคิดเห็น. |
| [getSlide()](#getSlide--) | คืนค่า หรือกำหนดสไลด์แม่ของความคิดเห็น. |
| [getAuthor()](#getAuthor--) | คืนค่าผู้เขียนของความคิดเห็น. |
| [getPosition()](#getPosition--) | คืนค่า หรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | คืนค่า หรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. |
| [remove()](#remove--) | ลบความคิดเห็นและการตอบกลับทั้งหมดจากคอลเลกชันแม่. |
| [getParentComment()](#getParentComment--) | รับหรือกำหนดความคิดเห็นแม่. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | รับหรือกำหนดความคิดเห็นแม่. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


คืนค่า หรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


คืนค่า หรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


คืนค่า หรือกำหนดเวลาการสร้างความคิดเห็น. การตั้งค่าแอตทริบิวต์นี้เป็น java.util.Date(Long.MIN_VALUE) หมายถึงไม่มีเวลาความคิดเห็นถูกตั้งค่า. อ่าน/เขียน java.util.Date.

--------------------

เวลาความคิดเห็นเป็นพารามิเตอร์ที่ไม่บังคับ.

**คืนค่า:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


คืนค่า หรือกำหนดเวลาการสร้างความคิดเห็น. การตั้งค่าแอตทริบิวต์นี้เป็น java.util.Date(Long.MIN_VALUE) หมายถึงไม่มีเวลาความคิดเห็นถูกตั้งค่า. อ่าน/เขียน java.util.Date.

--------------------

เวลาความคิดเห็นเป็นพารามิเตอร์ที่ไม่บังคับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```


คืนค่า หรือกำหนดสไลด์แม่ของความคิดเห็น. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


คืนค่าผู้เขียนของความคิดเห็น. อ่านอย่างเดียว [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**คืนค่า:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```


คืนค่า หรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```


คืนค่า หรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```


ลบความคิดเห็นและการตอบกลับทั้งหมดจากคอลเลกชันแม่.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


รับหรือกำหนดความคิดเห็นแม่. อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


รับหรือกำหนดความคิดเห็นแม่. อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject