---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: เป็นตัวแทนของคอมเมนต์บนสไลด์.
type: docs
url: /th/com.aspose.slides/icomment/
---```
public interface IComment
```

เป็นตัวแทนของคอมเมนต์บนสไลด์.
## วิธีการ

| เมธอด | รายละเอียด |
| --- | --- |
| [getText()](#getText--) | คืนค่าหรือกำหนดข้อความธรรมดาของคอมเมนต์บนสไลด์. |
| [setText(String value)](#setText-java.lang.String-) | คืนค่าหรือกำหนดข้อความธรรมดของคอมเมนต์บนสไลด์. |
| [getCreatedTime()](#getCreatedTime--) | คืนค่าหรือกำหนดเวลาการสร้างคอมเมนต์. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | คืนค่าหรือกำหนดเวลาการสร้างคอมเมนต์. |
| [getSlide()](#getSlide--) | คืนค่าหรือกำหนดสไลด์แม่ของคอมเมนต์. |
| [getAuthor()](#getAuthor--) | คืนค่าผู้เขียนของคอมเมนต์. |
| [getPosition()](#getPosition--) | คืนค่าหรือกำหนดตำแหน่งของคอมเมนต์บนสไลด์. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | คืนค่าหรือกำหนดตำแหน่งของคอมเมนต์บนสไลด์. |
| [remove()](#remove--) | ลบคอมเมนต์และการตอบกลับทั้งหมดจากคอลเลกชันแม่. |
| [getParentComment()](#getParentComment--) | รับหรือกำหนดคอมเมนต์แม่. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | รับหรือกำหนดคอมเมนต์แม่. |
### getText() {#getText--}
```
public abstract String getText()
```

คืนค่าหรือกำหนดข้อความธรรมดของคอมเมนต์บนสไลด์ อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

คืนค่าหรือกำหนดข้อความธรรมดของคอมเมนต์บนสไลด์ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

คืนค่าหรือกำหนดเวลาการสร้างคอมเมนต์ การตั้งค่าคุณสมบัตินี้เป็น java.util.Date(Long.MIN_VALUE) หมายความว่าไม่มีเวลาคอมเมนต์ตั้งค่าไว้ อ่าน/เขียน java.util.Date.

**คืนค่า:**
java.util.Date
--------------------

เวลาคอมเมนต์เป็นพารามิเตอร์แบบไม่บังคับ.

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

คืนค่าหรือกำหนดเวลาการสร้างคอมเมนต์ การตั้งค่าคุณสมบัตินี้เป็น java.util.Date(Long.MIN_VALUE) หมายความว่าไม่มีเวลาคอมเมนต์ตั้งค่าไว้ อ่าน/เขียน java.util.Date.

--------------------

เวลาคอมเมนต์เป็นพารามิเตอร์แบบไม่บังคับ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

คืนค่าหรือกำหนดสไลด์แม่ของคอมเมนต์ อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

คืนค่าผู้เขียนของคอมเมนต์ อ่านอย่างเดียว [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**คืนค่า:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

คืนค่าหรือกำหนดตำแหน่งของคอมเมนต์บนสไลด์ อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

คืนค่าหรือกำหนดตำแหน่งของคอมเมนต์บนสไลด์ อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

ลบคอมเมนต์และการตอบกลับทั้งหมดจากคอลเลกชันแม่.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

รับหรือกำหนดคอมเมนต์แม่ อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**คืนค่า:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

รับหรือกำหนดคอมเมนต์แม่ อ่าน/เขียน [IComment](../../com.aspose.slides/icomment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |