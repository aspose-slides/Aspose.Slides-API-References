---
title: MathAccent
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุฟังก์ชันการเน้นโดยประกอบด้วยฐานและเครื่องหมายการผสม ตัวอย่าง ud835udc4eu0301
type: docs
url: /th/com.aspose.slides/mathaccent/
---
**มรดก:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**ส่วนต่อประสานที่ทำไว้ทั้งหมด:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

กำหนดฟังก์ชันตัวเน้น ซึ่งประกอบด้วยฐานและเครื่องหมายการผสม ตัวอย่าง: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | The argument to which the accent was applied |
| [getCharacter()](#getCharacter--) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

สร้างตัวเน้นคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุโดยใช้ค่าตัวอักษรเน้นเริ่มต้น

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a math element to apply accent |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

สร้างตัวเน้นคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply accent |
| accentCharacter | char | accent character |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ที่มีการใช้ตัวเน้น

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

อักขระตัวเน้น ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**ผลลัพธ์:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

อักขระตัวเน้น ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับรายการลูกขององค์ประกอบ

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ผลลัพธ์:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps