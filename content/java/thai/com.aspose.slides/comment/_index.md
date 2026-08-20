---
title: Comment
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงความคิดเห็นบนสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/comment/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

แสดงถึงความคิดเห็นบนสไลด์.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // เพิ่มสไลด์ว่าง
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // เพิ่มผู้เขียน
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // ตั้งค่าตำแหน่งสำหรับความคิดเห็น
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // เพิ่มความคิดเห็นสไลด์สำหรับผู้เขียนบนสไลด์ 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // เพิ่มความคิดเห็นสไลด์สำหรับผู้เขียนบนสไลด์ 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// บันทึกไฟล์การนำเสนอ PowerPoint
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
>      // วนลูป CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // วนลูป Comments
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
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // เพิ่มการตอบกลับให้กับ comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // เพิ่มการตอบกลับอีกหนึ่งรายการให้กับ comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // เพิ่มการตอบกลับให้กับการตอบกลับที่มีอยู่
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // แสดงลำดับชั้นของความคิดเห็นบนคอนโซล
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
>      // ลบ comment1 และการตอบกลับทั้งหมดที่เกี่ยวข้อง
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getText()](#getText--) | เรียกคืนหรือกำหนดข้อความธรรมดาของความคิดเห็นบนสไลด์. |
| [setText(String value)](#setText-java.lang.String-) | เรียกคืนหรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. |
| [getCreatedTime()](#getCreatedTime--) | เรียกคืนหรือกำหนดเวลาการสร้างความคิดเห็น. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | เรียกคืนหรือกำหนดเวลาการสร้างความคิดเห็น. |
| [getSlide()](#getSlide--) | เรียกคืนหรือกำหนดสไลด์แม่ของความคิดเห็น. |
| [getAuthor()](#getAuthor--) | เรียกคืนผู้เขียนของความคิดเห็น. |
| [getPosition()](#getPosition--) | เรียกคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | เรียกคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. |
| [remove()](#remove--) | ลบความคิดเห็นและการตอบกลับทั้งหมดจากคอลเลกชันแม่. |
| [getParentComment()](#getParentComment--) | ดึงหรือกำหนดความคิดเห็นแม่. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | ดึงหรือกำหนดความคิดเห็นแม่. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

เรียกคืนหรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

เรียกคืนหรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

เรียกคืนหรือกำหนดเวลาการสร้างความคิดเห็น. การตั้งค่าคุณลักษณะนี้เป็น java.util.Date(Long.MIN_VALUE) หมายความว่าไม่มีเวลาความคิดเห็นที่ตั้งค่าไว้. อ่าน/เขียน java.util.Date.

--------------------

เวลาความคิดเห็นเป็นพารามิเตอร์ที่ไม่บังคับ.

**ผลลัพธ์:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

เรียกคืนหรือกำหนดเวลาการสร้างความคิดเห็น. การตั้งค่าคุณลักษณะนี้เป็น java.util.Date(Long.MIN_VALUE) หมายความว่าไม่มีเวลาความคิดเห็นที่ตั้งค่าไว้. อ่าน/เขียน java.util.Date.

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

เรียกคืนหรือกำหนดสไลด์แม่ของความคิดเห็น. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**ผลลัพธ์:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

เรียกคืนผู้เขียนของความคิดเห็น. อ่านอย่างเดียว [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**ผลลัพธ์:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

เรียกคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. อ่าน/เขียน java.awt.geom.Point2D.Float.

**ผลลัพธ์:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

เรียกคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

ลบความคิดเห็นและการตอบกลับทั้งหมดจากคอลเลกชันแม่.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

ดึงหรือกำหนดความคิดเห็นแม่. อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**ผลลัพธ์:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

ดึงหรือกำหนดความคิดเห็นแม่. อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

เรียกคืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject