---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: แสดงความคิดเห็นบนสไลด์.
type: docs
url: /th/com.aspose.slides/icomment/
---```
public interface IComment
```

แสดงความคิดเห็นบนสไลด์.
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getText()](#getText--) | ส่งคืนหรือกำหนดข้อความธรรมดาของความคิดเห็นบนสไลด์. |
| [setText(String value)](#setText-java.lang.String-) | ส่งคืนหรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. |
| [getCreatedTime()](#getCreatedTime--) | ส่งคืนหรือกำหนดเวลาการสร้างความคิดเห็น. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | ส่งคืนหรือกำหนดเวลาการสร้างความคิดเห็น. |
| [getSlide()](#getSlide--) | ส่งคืนหรือกำหนดสไลด์แม่ของความคิดเห็น. |
| [getAuthor()](#getAuthor--) | ส่งคืนผู้เขียนของความคิดเห็น. |
| [getPosition()](#getPosition--) | ส่งคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | ส่งคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. |
| [remove()](#remove--) | ลบความคิดเห็นและการตอบกลับทั้งหมดจากคอลเลกชันแม่. |
| [getParentComment()](#getParentComment--) | รับหรือกำหนดความคิดเห็นแม่. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | รับหรือกำหนดความคิดเห็นแม่. |
### getText() {#getText--}
```
public abstract String getText()
```

ส่งคืนหรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

ส่งคืนหรือกำหนดข้อความธรรมดของความคิดเห็นบนสไลด์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

ส่งคืนหรือกำหนดเวลาการสร้างความคิดเห็น. การตั้งค่าคุณสมบัตินี้เป็น java.util.Date(Long.MIN_VALUE) หมายถึงไม่ได้ตั้งค่าเวลาให้กับความคิดเห็น. อ่าน/เขียน java.util.Date.

--------------------

เวลาแสดงความคิดเห็นเป็นพารามิเตอร์ทางเลือก.

**คืนค่า:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

ส่งคืนหรือกำหนดเวลาการสร้างความคิดเห็น. การตั้งค่าคุณสมบัตินี้เป็น java.util.Date(Long.MIN_VALUE) หมายถึงไม่ได้ตั้งค่าเวลาให้กับความคิดเห็น. อ่าน/เขียน java.util.Date.

--------------------

เวลาแสดงความคิดเห็นเป็นพารามิเตอร์ทางเลือก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

ส่งคืนหรือกำหนดสไลด์แม่ของความคิดเห็น. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

ส่งคืนผู้เขียนของความคิดเห็น. อ่านอย่างเดียว [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**คืนค่า:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

ส่งคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

ส่งคืนหรือกำหนดตำแหน่งของความคิดเห็นบนสไลด์. อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public abstract void remove()
```

ลบความคิดเห็นและการตอบกลับทั้งหมดจากคอลเลกชันแม่.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

รับหรือกำหนดความคิดเห็นแม่. อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

รับหรือกำหนดความคิดเห็นแม่. อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |