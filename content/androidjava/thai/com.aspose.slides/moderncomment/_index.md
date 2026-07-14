---
title: ModernComment
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงความคิดเห็นบนสไลด์
type: docs
url: /th/com.aspose.slides/moderncomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**All Implemented Interfaces:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

แสดงถึงความคิดเห็นบนสไลด์หนึ่ง.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| Method | Description |
| --- | --- |
| [getShape()](#getShape--) | ส่งคืนรูปทรงที่เชื่อมโยงกับความคิดเห็นนี้. |
| [getTextSelectionStart()](#getTextSelectionStart--) | รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | รับหรือกำหนดความยาวของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | รับหรือกำหนดความยาวของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. |
| [getStatus()](#getStatus--) | รับหรือกำหนดสถานะของความคิดเห็น. |
| [setStatus(byte value)](#setStatus-byte-) | รับหรือกำหนดสถานะของความคิดเห็น. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```



ส่งคืนรูปทรงที่เชื่อมโยงกับความคิดเห็นนี้. อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**ผลลัพธ์:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


รับหรือกำหนดความยาวของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


รับหรือกำหนดความยาวของการเลือกข้อความในกรอบข้อความหากความคิดเห็นเชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


รับหรือกำหนดสถานะของความคิดเห็น. อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**ผลลัพธ์:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


รับหรือกำหนดสถานะของความคิดเห็น. อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


ส่งคืนอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject