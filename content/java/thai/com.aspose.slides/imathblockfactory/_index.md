---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้างบล็อกคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

อนุญาตให้สร้างบล็อกคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | สร้างบล็อกคณิตศาสตร์ |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | สร้างบล็อกคณิตศาสตร์และวางองค์ประกอบลงในบล็อก |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | สร้างบล็อกคณิตศาสตร์และวางหลายองค์ประกอบลงในบล็อก |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

สร้างบล็อกคณิตศาสตร์

**คืนค่า:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์ใหม่
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

สร้างบล็อกคณิตศาสตร์และวางองค์ประกอบลงในบล็อก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ |

**คืนค่า:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์ใหม่
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

สร้างบล็อกคณิตศาสตร์และวางหลายองค์ประกอบลงในบล็อก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | องค์ประกอบคณิตศาสตร์ |

**คืนค่า:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์ใหม่