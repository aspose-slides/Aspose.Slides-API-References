---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math paragraph
type: docs
url: /th/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

อนุญาตให้สร้างย่อหน้าคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | สร้างย่อหน้าคณิตศาสตร์เปล่า |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | สร้างย่อหน้าคณิตศาสตร์และวางบล็อกคณิตศาสตร์ที่ระบุลงในมัน |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


สร้างย่อหน้าคณิตศาสตร์เปล่า

**ค่าที่ส่งกลับ:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


สร้างย่อหน้าคณิตศาสตร์และวางบล็อกคณิตศาสตร์ที่ระบุลงในมัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกคณิตศาสตร์ที่ต้องวางในย่อหน้า |

**ค่าที่ส่งกลับ:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่