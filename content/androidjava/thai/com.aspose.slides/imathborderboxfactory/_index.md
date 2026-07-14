---
title: IMathBorderBoxFactory
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อนุญาตให้สร้างกล่องขอบคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

อนุญาตให้สร้างกล่องขอบคณิตศาสตร์

--------------------

เพื่อความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | สร้างกล่องขอบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | สร้างกล่องขอบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

สร้างกล่องขอบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์สำหรับใส่กล่องขอบ |

**ผลลัพธ์:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - องค์ประกอบกล่องขอบใหม่
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

สร้างกล่องขอบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์สำหรับใส่กล่องขอบ |
| hideTop | boolean | ซ่อนขอบบน |
| hideBottom | boolean | ซ่อนขอบล่าง |
| hideLeft | boolean | ซ่อนขอบซ้าย |
| hideRight | boolean | ซ่อนขอบขวา |
| strikethroughHorizontal | boolean | เส้นขีดฆ่ากล่องขอบแนวนอน |
| strikethroughVertical | boolean | เส้นขีดฆ่ากล่องขอบแนวดิ่ง |
| strikethroughBottomLeftToTopRight | boolean | เส้นขีดฆ่ากล่องขอบจากมุมล่างซ้ายไปมุมบนขวา |
| strikethroughTopLeftToBottomRight | boolean | เส้นขีดฆ่ากล่องขอบจากมุมบนซ้ายไปมุมล่างขวา |

**ผลลัพธ์:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - องค์ประกอบกล่องขอบใหม่