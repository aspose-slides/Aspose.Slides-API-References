---
title: IMathRadical
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุฟังก์ชันรากที่ประกอบด้วย base และ degree ที่เป็นตัวเลือก.
type: docs
url: /th/com.aspose.slides/imathradical/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

ระบุฟังก์ชันรากที่ประกอบด้วย base และ degree ที่เป็นตัวเลือก ตัวอย่างของอ็อบเจ็กต์รากคือ \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | Base อาร์กิวเมนต์ |
| [getDegree()](#getDegree--) | Degree อาร์กิวเมนต์ |
| [getHideDegree()](#getHideDegree--) | Hide degree เมื่อเป็น true, degree จะไม่แสดง, เช่น \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree เมื่อเป็น true, degree จะไม่แสดง, เช่น \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base อาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
>  IMathElement baseElem = radical.getBase();
>  ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Degree อาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
>  IMathElement degreeElem = radical.getDegree();
>  ```


**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree เมื่อเป็น true, degree จะไม่แสดง, เช่น \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
>  radical.setHideDegree(true);
> ```

**คืนค่า:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree เมื่อเป็น true, degree จะไม่แสดง, เช่น \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
>  radical.setHideDegree(true);
>  ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |