---
title: IMathRadical
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุฟังก์ชันรากที่ประกอบด้วยฐานและระดับที่เป็นตัวเลือก.
type: docs
url: /th/com.aspose.slides/imathradical/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

ระบุฟังก์ชันรากที่ประกอบด้วยฐานและระดับที่เป็นตัวเลือก ตัวอย่างของอ็อบเจกต์รากคือ \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getDegree()](#getDegree--) | อาร์กิวเมนต์ระดับ |
| [getHideDegree()](#getHideDegree--) | ซ่อนระดับ ถ้าเป็น true, ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | ซ่อนระดับ ถ้าเป็น true, ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


อาร์กิวเมนต์ฐาน

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


อาร์กิวเมนต์ระดับ

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
>  IMathElement degreeElem = radical.getDegree();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


ซ่อนระดับ ถ้าเป็น true, ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // รากลูกบาศก์
>  radical.setHideDegree(true);
>  ```

**คืนค่า:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


ซ่อนระดับ ถ้าเป็น true, ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65

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