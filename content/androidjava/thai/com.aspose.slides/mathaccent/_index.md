---
title: MathAccent
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุฟังก์ชันการเน้นเสียงที่ประกอบด้วยฐานและเครื่องหมายวรรณยุกต์ที่รวมเข้าด้วยกัน ตัวอย่าง ud835udc4eu0301
type: docs
url: /th/com.aspose.slides/mathaccent/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**ส่วนติดต่อที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

ระบุฟังก์ชันการเน้นเสียงโดยประกอบด้วยฐานและเครื่องหมายวรรณยุกต์ที่รวมเข้าด้วยกัน ตัวอย่าง: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | สร้าง math accent ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุด้วยค่าตัวอักษร accent เริ่มต้น |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | สร้าง math accent ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ที่ถูกใช้กับ accent |
| [getCharacter()](#getCharacter--) | Accent Character ค่าควรอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character ค่าควรอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | ดึงเอาองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักขระควบคุม |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


สร้าง math accent ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุด้วยค่าตัวอักษร accent เริ่มต้น

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะนำ accent ไปใช้ |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


สร้าง math accent ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะนำ accent ไปใช้ |
| accentCharacter | char | ตัวอักษร accent |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


อาร์กิวเมนต์ที่ถูกใช้กับ accent

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


Accent Character ค่าควรอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

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


Accent Character ค่าควรอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


ดึงเอาองค์ประกอบลูก

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


คุณสมบัติตัวอักขระควบคุม

**ผลลัพธ์:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps