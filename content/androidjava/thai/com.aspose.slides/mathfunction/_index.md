---
title: MathFunction
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุฟังก์ชันของอาร์กิวเมนต์
type: docs
url: /th/com.aspose.slides/mathfunction/
---
**Inheritance:**  
การสืบทอด: java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
ส่วนต่อประสานที่นำไปใช้ทั้งหมด: [com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

ระบุฟังก์ชันของอาร์กิวเมนต์.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างอินสแตนซ์ใหม่ของคลาส MathFunction |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | สร้างอินสแตนซ์ใหม่ของคลาส MathFunction |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชันคือ sin และ cos |
| [getBase()](#getBase--) | อาร์กิวเมนต์ของฟังก์ชัน |
| [getChildren()](#getChildren--) | รับสมาชิกย่อย |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathFunction

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathFunction

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```

ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชันคือ sin และ cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**ค่าที่ส่งคืน:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ของฟังก์ชัน

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**ค่าที่ส่งคืน:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับสมาชิกย่อย

**ค่าที่ส่งคืน:**
com.aspose.slides.IMathElement[] - อาเรย์ของ [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ค่าที่ส่งคืน:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps