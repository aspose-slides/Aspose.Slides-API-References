---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math grouping character
type: docs
url: /th/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

อนุญาตให้สร้างตัวอักษรกลุ่มคณิตศาสตร์

--------------------

สำหรับการเปรียบเทียบกับ COM
## เมธอด

| Method | Description |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | สร้างตัวอักษรกลุ่มคณิตศาสตร์ |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | สร้างตัวอักษรกลุ่มคณิตศาสตร์ |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


สร้างตัวอักษรกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์คณิตศาสตร์เพื่อใช้ตัวอักษรกลุ่ม |
| character | char | ตัวอักษรกลุ่ม |
| position | int | ตำแหน่งของตัวอักษรกลุ่ม |
| verticalJustification | int | การจัดแนวแนวตั้ง |

**ค่าที่คืนกลับ:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อิลิเมนต์ตัวอักษรกลุ่มใหม่
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


สร้างตัวอักษรกลุ่มคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์คณิตศาสตร์เพื่อใช้ตัวอักษรกลุ่ม |

**ค่าที่คืนกลับ:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - อิลิเมนต์ตัวอักษรกลุ่มใหม่