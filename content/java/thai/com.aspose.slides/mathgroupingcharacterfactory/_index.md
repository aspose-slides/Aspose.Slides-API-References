---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: อนุญาตให้สร้างอักขระการจัดกลุ่มคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathgroupingcharacterfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

อนุญาตให้สร้างอักขระการจัดกลุ่มคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## ตัวสร้าง

| Constructor | คำอธิบาย |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | สร้างอักขระการจัดกลุ่มคณิตศาสตร์ |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | สร้างอักขระการจัดกลุ่มคณิตศาสตร์ |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

สร้างอักขระการจัดกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่ต้องการเพิ่มอักขระการจัดกลุ่ม |
| character | char | อักขระการจัดกลุ่ม |
| position | int | ตำแหน่งของอักขระการจัดกลุ่ม |
| verticalJustification | int | การจัดแนวแนวตั้ง |

**ผลลัพธ์:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อักขระการจัดกลุ่มใหม่
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

สร้างอักขระการจัดกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่ต้องการเพิ่มอักขระการจัดกลุ่ม |

**ผลลัพธ์:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อักขระการจัดกลุ่มใหม่