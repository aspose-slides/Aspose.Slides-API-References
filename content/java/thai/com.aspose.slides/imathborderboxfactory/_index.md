---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้างกล่องขอบคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

อนุญาตให้สร้างกล่องขอบคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | สร้างกล่องขอบคณิตศาสตร์โดยใช้กับองค์ประกอบ |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | สร้างกล่องขอบคณิตศาสตร์โดยใช้กับองค์ประกอบ |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

สร้างกล่องขอบคณิตศาสตร์โดยใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์คณิตศาสตร์ที่ใช้กับกล่องขอบ |

**คืนค่า:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - อิลิเมนต์กล่องขอบใหม่
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

สร้างกล่องขอบคณิตศาสตร์โดยใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์คณิตศาสตร์ที่ใช้กับกล่องขอบ |
| hideTop | boolean | ซ่อนขอบบน |
| hideBottom | boolean | ซ่อนขอบล่าง |
| hideLeft | boolean | ซ่อนขอบซ้าย |
| hideRight | boolean | ซ่อนขอบขวา |
| strikethroughHorizontal | boolean | เส้นขีดฆ่าตามแนวนอนของกล่องขอบ |
| strikethroughVertical | boolean | เส้นขีดฆ่าตามแนวตั้งของกล่องขอบ |
| strikethroughBottomLeftToTopRight | boolean | เส้นขีดฆ่าจากซ้ายล่างไปขวาบนของกล่องขอบ |
| strikethroughTopLeftToBottomRight | boolean | เส้นขีดฆ่าจากซ้ายบนไปขวาล่างของกล่องขอบ |

**คืนค่า:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - อิลิเมนต์กล่องขอบใหม่