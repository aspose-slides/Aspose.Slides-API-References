---
title: MathBorderBoxFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API
description: อนุญาตให้สร้างกล่องขอบคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathborderboxfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

อนุญาตให้สร้างกล่องขอบคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | สร้างกล่องขอบคณิตศาสตร์โดยประมวลผลกับองค์ประกอบ |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | สร้างกล่องขอบคณิตศาสตร์โดยประมวลผลกับองค์ประกอบ |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


สร้างกล่องขอบคณิตศาสตร์โดยประมวลผลกับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ส่วนประกอบคณิตศาสตร์เพื่อใช้กำหนดกล่องขอบ |

**ผลลัพธ์:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - องค์ประกอบกล่องขอบใหม่
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


สร้างกล่องขอบคณิตศาสตร์โดยประมวลผลกับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ส่วนประกอบคณิตศาสตร์เพื่อใช้กำหนดกล่องขอบ |
| hideTop | boolean | ซ่อนขอบบน |
| hideBottom | boolean | ซ่อนขอบล่าง |
| hideLeft | boolean | ซ่อนขอบซ้าย |
| hideRight | boolean | ซ่อนขอบขวา |
| strikethroughHorizontal | boolean | ขีดเส้นแนวนอนในกล่องขอบ |
| strikethroughVertical | boolean | ขีดเส้นแนวตั้งในกล่องขอบ |
| strikethroughBottomLeftToTopRight | boolean | ขีดเส้นจากซ้ายล่างไปขวาบนในกล่องขอบ |
| strikethroughTopLeftToBottomRight | boolean | ขีดเส้นจากซ้ายบนไปขวาล่างในกล่องขอบ |

**ผลลัพธ์:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - องค์ประกอบกล่องขอบใหม่