---
title: MathAccentFactory
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: อนุญาตให้สร้างตัวเน้นคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathaccentfactory/
---
**สืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)  
```
public class MathAccentFactory implements IMathAccentFactory
```

อนุญาตให้สร้างตัวเน้นคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้ของ COM
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | สร้างตัวเน้นคณิตศาสตร์ที่นำไปใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุโดยใช้ค่าตัวอักษรเน้นเริ่มต้น |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | สร้างตัวเน้นคณิตศาสตร์ที่นำไปใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ |

### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

สร้างตัวเน้นคณิตศาสตร์ที่นำไปใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุโดยใช้ค่าตัวอักษรเน้นเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่ต้องการใส่ตัวเน้น |

**ค่าที่คืน:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - ตัวเน้นคณิตศาสตร์ใหม่

### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

สร้างตัวเน้นคณิตศาสตร์ที่นำไปใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่ต้องการใส่ตัวเน้น |
| accentCharacter | char | ตัวอักษรเน้น |

**ค่าที่คืน:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - ตัวเน้นคณิตศาสตร์ใหม่