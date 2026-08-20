---
title: IMathParagraphFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้างย่อหน้าคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

อนุญาตให้สร้างย่อหน้าคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Create empty math paragraph |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Creates a math paragraph and places the specified math block in it |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


สร้างย่อหน้าคณิตศาสตร์เปล่า

**คืนค่า:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


สร้างย่อหน้าคณิตศาสตร์และใส่บล็อกคณิตศาสตร์ที่ระบุลงในนั้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกคณิตศาสตร์ที่จะใส่ในย่อหน้า |

**คืนค่า:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่