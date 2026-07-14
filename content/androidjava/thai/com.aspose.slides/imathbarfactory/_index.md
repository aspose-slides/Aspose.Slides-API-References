---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math bar
type: docs
url: /th/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

อนุญาตให้สร้างแถบคณิตศาสตร์

--------------------

เพื่อความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | สร้างแถบคณิตศาสตร์โดยการนำไปใช้กับองค์ประกอบ |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | สร้างแถบคณิตศาสตร์โดยการนำไปใช้กับองค์ประกอบ |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

สร้างแถบคณิตศาสตร์โดยการนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์สำหรับใส่แถบ |

**คืนค่า:**
[IMathBar](../../com.aspose.slides/imathbar) - แถบคณิตศาสตร์ใหม่
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

สร้างแถบคณิตศาสตร์โดยการนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์สำหรับใส่แถบ |
| position | int | ตำแหน่งของแถบ |

**คืนค่า:**
[IMathBar](../../com.aspose.slides/imathbar) - แถบคณิตศาสตร์ใหม่