---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อนุญาตให้สร้างตัวอักษรจัดกลุ่มคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathgroupingcharacterfactory/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ทำทั้งหมด:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

อนุญาตให้สร้างตัวอักษรจัดกลุ่มคณิตศาสตร์

--------------------

เพื่อความเข้ากันได้กับ COM
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | สร้างตัวอักษรจัดกลุ่มคณิตศาสตร์ |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | สร้างตัวอักษรจัดกลุ่มคณิตศาสตร์ |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

สร้างตัวอักษรจัดกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะนำตัวอักษรจัดกลุ่มไปใช้ |
| character | char | ตัวอักษรจัดกลุ่ม |
| position | int | ตำแหน่งของตัวอักษรจัดกลุ่ม |
| verticalJustification | int | การจัดแนวในแนวตั้ง |

**ค่าที่ส่งกลับ:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อิลีเมนต์ตัวอักษรจัดกลุ่มใหม่
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

สร้างตัวอักษรจัดกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะนำตัวอักษรจัดกลุ่มไปใช้ |

**ค่าที่ส่งกลับ:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อิลีเมนต์ตัวอักษรจัดกลุ่มใหม่