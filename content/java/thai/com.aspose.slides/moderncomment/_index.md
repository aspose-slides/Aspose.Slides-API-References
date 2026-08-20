---
title: ModernComment
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เป็นการแทนความเห็นบนสไลด์.
type: docs
url: /th/com.aspose.slides/moderncomment/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject  
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

เป็นการแทนความเห็นบนสไลด์.

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
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShape()](#getShape--) | คืน shape ที่เชื่อมโยงกับคอมเมนต์. |
| [getTextSelectionStart()](#getTextSelectionStart--) | รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | รับหรือกำหนดความยาวของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | รับหรือกำหนดความยาวของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. |
| [getStatus()](#getStatus--) | รับหรือกำหนดสถานะของคอมเมนต์. |
| [setStatus(byte value)](#setStatus-byte-) | รับหรือกำหนดสถานะของคอมเมนต์. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

คืน shape ที่เชื่อมโยงกับคอมเมนต์. อ่านอย่างเดียว [IShape](../../com.aspose.slides/ishape).

**คืนค่า:**  
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**คืนค่า:**  
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

รับหรือกำหนดตำแหน่งเริ่มต้นของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

รับหรือกำหนดความยาวของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**คืนค่า:**  
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

รับหรือกำหนดความยาวของการเลือกข้อความใน text frame หากคอมเมนต์เชื่อมโยงกับ AutoShape. อ่าน/เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

รับหรือกำหนดสถานะของคอมเมนต์. อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**คืนค่า:**  
byte

### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

รับหรือกำหนดสถานะของคอมเมนต์. อ่าน/เขียน [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject