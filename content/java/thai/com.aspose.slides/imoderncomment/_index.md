---
title: IModernComment
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวแทนของความคิดเห็นบนสไลด์.
type: docs
url: /th/com.aspose.slides/imoderncomment/
---
**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Represents a comment on a slide.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShape()](#getShape--) | คืนค่า shape ที่เชื่อมโยงกับความคิดเห็น |
| [getTextSelectionStart()](#getTextSelectionStart--) | คืนค่า หรือ ตั้งค่า ตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | คืนค่า หรือ ตั้งค่า ตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape |
| [getTextSelectionLength()](#getTextSelectionLength--) | คืนค่า หรือ ตั้งค่า ความยาวของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | คืนค่า หรือ ตั้งค่า ความยาวของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape |
| [getStatus()](#getStatus--) | คืนค่า หรือ ตั้งค่า status ของความคิดเห็น |
| [setStatus(byte value)](#setStatus-byte-) | คืนค่า หรือ ตั้งค่า status ของความคิดเห็น |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


คืนค่า shape ที่เชื่อมโยงกับความคิดเห็น. อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


คืนค่า หรือ ตั้งค่า ตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


คืนค่า หรือ ตั้งค่า ตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


คืนค่า หรือ ตั้งค่า ความยาวของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


คืนค่า หรือ ตั้งค่า ความยาวของการเลือกข้อความใน text frame หากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


คืนค่า หรือ ตั้งค่า status ของความคิดเห็น. อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**ผลลัพธ์:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


คืนค่า หรือ ตั้งค่า status ของความคิดเห็น. อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |