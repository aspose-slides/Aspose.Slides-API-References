---
title: IMathAccentFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้างเครื่องหมายคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

อนุญาตให้สร้างเครื่องหมายคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้ของ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุพร้อมค่าตัวอักษรเครื่องหมายเริ่มต้น |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุพร้อมค่าตัวอักษรเครื่องหมายเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะใส่เครื่องหมาย |

**คืนค่า:**
[IMathAccent](../../com.aspose.slides/imathaccent) - เครื่องหมายคณิตศาสตร์ใหม่
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะใส่เครื่องหมาย |
| accentCharacter | char | อักขระเครื่องหมาย |

**คืนค่า:**
[IMathAccent](../../com.aspose.slides/imathaccent) - เครื่องหมายคณิตศาสตร์ใหม่