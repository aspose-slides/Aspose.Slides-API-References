---
title: IModernComment
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนความหมายของคอมเมนต์บนสไลด์.
type: docs
url: /th/com.aspose.slides/imoderncomment/
---
**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

แทนความหมายของคอมเมนต์บนสไลด์

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

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShape()](#getShape--) | ส่งคืนรูปร่างที่เชื่อมโยงกับคอมเมนต์ |
| [getTextSelectionStart()](#getTextSelectionStart--) | ส่งคืนหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | ส่งคืนหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape |
| [getTextSelectionLength()](#getTextSelectionLength--) | ส่งคืนหรือกำหนดความยาวการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | ส่งคืนหรือกำหนดความยาวการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape |
| [getStatus()](#getStatus--) | ส่งคืนหรือกำหนดสถานะของคอมเมนต์ |
| [setStatus(byte value)](#setStatus-byte-) | ส่งคืนหรือกำหนดสถานะของคอมเมนต์ |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


ส่งคืนรูปร่างที่เชื่อมโยงกับคอมเมนต์ อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


ส่งคืนหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape อ่าน/เขียน int.

**คืนค่า:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


ส่งคืนหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


ส่งคืนหรือกำหนดความยาวการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape อ่าน/เขียน int.

**คืนค่า:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


ส่งคืนหรือกำหนดความยาวการเลือกข้อความในกรอบข้อความหากคอมเมนต์เชื่อมโยงกับ AutoShape อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


ส่งคืนหรือกำหนดสถานะของคอมเมนต์ อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**คืนค่า:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


ส่งคืนหรือกำหนดสถานะของคอมเมนต์ อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |