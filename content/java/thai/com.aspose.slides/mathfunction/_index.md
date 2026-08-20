---
title: MathFunction
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุฟังก์ชันของอาร์กิวเมนต์.
type: docs
url: /th/com.aspose.slides/mathfunction/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

ระบุฟังก์ชันของอาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathFunction |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathFunction |
## เมธอด

| Method | Description |
| --- | --- |
| [getName()](#getName--) | ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชันคือ sin และ cos |
| [getBase()](#getBase--) | อาร์กิวเมนต์ของฟังก์ชัน |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathFunction

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathFunction

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**พารามิเตอร์:**  
| Parameter | Type | Description |
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

**ผลลัพธ์:**  
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

**ผลลัพธ์:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

ดึงองค์ประกอบลูก

**ผลลัพธ์:**  
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ผลลัพธ์:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps