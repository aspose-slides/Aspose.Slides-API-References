---
title: MathParagraphFactory
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: อนุญาตให้สร้างย่อหน้าคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathparagraphfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)  
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Allows to create a math paragraph  
**สำหรับการทำให้เข้ากันได้กับ COM**

--------------------

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Create empty math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Creates a math paragraph and places the specified math block in it |

### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```

### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```

สร้างย่อหน้าคณิตศาสตร์เปล่า

**คืนค่า:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่

### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

สร้างย่อหน้าคณิตศาสตร์และวางบล็อกคณิตศาสตร์ที่ระบุไว้ในนั้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกคณิตศาสตร์ที่จะวางในย่อหน้า |

**คืนค่า:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่