---
title: IMathAccent
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API
description: ระบุฟังก์ชันการใส่สำเนียงซึ่งประกอบด้วยฐานและเครื่องหมายสัญลักษณ์ประกอบ ตัวอย่าง ud835udc4eu0301
type: docs
url: /th/com.aspose.slides/imathaccent/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

กำหนดฟังก์ชันการใส่สำเนียง, ประกอบด้วยฐานและเครื่องหมายเชื่อมต่อ ตัวอย่าง: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ที่ถูกใส่สำเนียง |
| [getCharacter()](#getCharacter--) | อักขระสำเนียง ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | อักขระสำเนียง ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


อาร์กิวเมนต์ที่ถูกใส่สำเนียง

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


อักขระสำเนียง ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**คืนค่า:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


อักขระสำเนียง ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

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