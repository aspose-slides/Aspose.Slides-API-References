---
title: IMathAccent
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ระบุฟังก์ชันสำเนียงซึ่งประกอบด้วยฐานและเครื่องหมายการผสม ตัวอย่าง ud835udc4eu0301
type: docs
url: /th/com.aspose.slides/imathaccent/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

ระบุฟังก์ชันสำเนียง ซึ่งประกอบด้วยฐานและเครื่องหมายการผสม ตัวอย่าง: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## เมธอด

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ที่มีการใช้สำเนียง |
| [getCharacter()](#getCharacter--) | อักขระสำเนียง ค่าควรอยู่ในช่วง (U+0300–U+036F) หรือ (U+20D0–U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | อักขระสำเนียง ค่าควรอยู่ในช่วง (U+0300–U+036F) หรือ (U+20D0–U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


อาร์กิวเมนต์ที่มีการใช้สำเนียง

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


อักขระสำเนียง ค่าควรอยู่ในช่วง (U+0300–U+036F) หรือ (U+20D0–U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
>  ```


**คืนค่า:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


อักขระสำเนียง ค่าควรอยู่ในช่วง (U+0300–U+036F) หรือ (U+20D0–U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |