---
title: MathBlockFactory
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: อนุญาตให้สร้างบล็อกคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathblockfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

อนุญาตให้สร้างบล็อกคณิตศาสตร์

--------------------

เพื่อความเข้ากันได้กับ COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | สร้างบล็อกคณิตศาสตร์ |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | สร้างบล็อกคณิตศาสตร์และวางอิลิเมนต์ไว้ในบล็อก |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | สร้างบล็อกคณิตศาสตร์และวางอิลิเมนต์หลายรายการไว้ในบล็อก |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


สร้างบล็อกคณิตศาสตร์

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์ใหม่
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


สร้างบล็อกคณิตศาสตร์และวางอิลิเมนต์ไว้ในบล็อก

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์คณิตศาสตร์ |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์ใหม่
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


สร้างบล็อกคณิตศาสตร์และวางอิลิเมนต์หลายรายการไว้ในบล็อก

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | อิลิเมนต์คณิตศาสตร์ |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์ใหม่