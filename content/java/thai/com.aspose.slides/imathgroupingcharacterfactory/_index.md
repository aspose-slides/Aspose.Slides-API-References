---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้างตัวอักษรกลุ่มคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

อนุญาตให้สร้างตัวอักษรกลุ่มคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | สร้างตัวอักษรกลุ่มคณิตศาสตร์ |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | สร้างตัวอักษรกลุ่มคณิตศาสตร์ |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

สร้างตัวอักษรกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่ใช้กับตัวอักษรกลุ่ม |
| character | char | อักษรกลุ่ม |
| position | int | ตำแหน่งของอักษรกลุ่ม |
| verticalJustification | int | การจัดตำแหน่งแนวตั้ง |

**ส่งคืน:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - ตัวประกอบอักษรกลุ่มใหม่
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

สร้างตัวอักษรกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่ใช้กับตัวอักษรกลุ่ม |

**ส่งคืน:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - ตัวประกอบอักษรกลุ่มใหม่