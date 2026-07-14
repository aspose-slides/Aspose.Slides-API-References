---
title: MathParagraphFactory
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อนุญาตให้สร้างย่อหน้าคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathparagraphfactory/
---
**Inheritance:**  
การสืบทอด:
java.lang.Object

**All Implemented Interfaces:**  
ทุกอินเตอร์เฟซที่ทำการนำมาใช้:
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

อนุญาตให้สร้างย่อหน้าคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## เมธอด

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | สร้างย่อหน้าคณิตศาสตร์เปล่า |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | สร้างย่อหน้าคณิตศาสตร์และวางบล็อกคณิตศาสตร์ที่ระบุไว้ในนั้น |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```

### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```

สร้างย่อหน้าคณิตศาสตร์เปล่า

**Returns:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

สร้างย่อหน้าคณิตศาสตร์และวางบล็อกคณิตศาสตร์ที่ระบุไว้ในนั้น

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกคณิตศาสตร์ที่จะวางในย่อหน้า |

**Returns:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - ย่อหน้าคณิตศาสตร์ใหม่